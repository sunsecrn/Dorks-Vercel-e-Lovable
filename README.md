# 🕵️‍♂️ Dorks para Encontrar Sites Falsos na Lovable & Vercel

[![Contribuições bem-vindas](https://img.shields.io/badge/contribui%C3%A7%C3%B5es-bem--vindas-brightgreen)](CONTRIBUTING.md)
[![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-blue.svg)](LICENSE)

Bem-vindo ao repositório **Dorks para Encontrar Sites Falsos na Lovable & Vercel**! Aqui você encontrará uma curadoria de Google Dorks para identificar páginas fraudulentas hospedadas nessas plataformas. Nosso objetivo é fortalecer a comunidade de segurança digital, facilitando a detecção e o reporte de sites maliciosos.

---

## ✨ Motivação

Com o crescimento de plataformas como Lovable e Vercel, criminosos têm aproveitado a facilidade de deploy para hospedar páginas de phishing, scam e outros golpes. Este repositório visa:

- 🔍 Facilitar a busca por sites falsos usando Google Dorks
- 🛡️ Ajudar pesquisadores e profissionais de segurança
- 🚨 Promover o reporte de ameaças às plataformas responsáveis

---

## 🧑‍💻 O que são Google Dorks?

Google Dorks são consultas avançadas que utilizam operadores especiais do Google para encontrar informações específicas em sites indexados. São amplamente usadas em pesquisas de segurança para localizar vulnerabilidades, arquivos expostos e, neste caso, páginas falsas.

---

## 🚀 Como Usar

1. Escolha uma dork da lista abaixo.
2. Cole a consulta na barra de pesquisa do Google.
3. Analise os resultados e, se encontrar um site suspeito, reporte à plataforma.

> **Dica:** Combine operadores para refinar ainda mais sua busca!

---

## 📚 Exemplos de Dorks

## 🏦 Dorks Específicas para Auxílio e Empréstimo no Vercel & Lovable

Aqui estão dorks avançadas para identificar golpes relacionados a empréstimos, benefícios do governo e fraudes financeiras nessas plataformas. Cada dork é acompanhada de uma breve explicação:

---

### 💰 1. Dork – Empréstimo / crédito fácil (dados sensíveis)

Busca páginas que prometem empréstimo aprovado ou crédito fácil e solicitam dados sensíveis como CPF ou senha.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"empréstimo aprovado" OR intext:"crédito liberado" OR intext:"empréstimo consignado") (intext:"CPF" OR intext:"confirme seus dados" OR intext:"senha")
```

---

### 🧾 2. Dork – Auxílio do governo (falsos benefícios ou prova de vida)

Encontra páginas que simulam benefícios do governo ou prova de vida, geralmente pedindo CPF ou login.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"auxílio emergencial" OR intext:"auxílio brasil" OR intext:"benefício do governo" OR intext:"prova de vida") (intext:"CPF" OR intext:"login")
```

---

### 🎣 3. Dork – Interfaces falsas de acesso (login + senha + CPF)

Procura páginas de login falsas que pedem CPF, senha e mencionam auxílio ou empréstimo.

```plaintext
(site:vercel.app OR site:lovable.site) (intitle:"login" OR inurl:"login") (intext:"CPF" OR intext:"senha") (intext:"auxílio" OR intext:"empréstimo")
```

---

### 💸 4. Dork – Pagamento antecipado ou taxas suspeitas

Busca páginas que exigem pagamento antecipado ou taxas para liberar empréstimos, um sinal clássico de golpe.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"taxa antecipada" OR intext:"liberação imediata" OR intext:"pague a primeira parcela") (intext:"empréstimo")
```

---

### 🔍 5. Dork – URLs com nomes enganosos (golpes disfarçados de programas oficiais)

Encontra URLs que tentam se passar por programas oficiais, usando termos como auxílio, empréstimo, benefício ou gov.

```plaintext
(site:vercel.app OR site:lovable.site) (inurl:"auxilio" OR inurl:"emprestimo" OR inurl:"beneficio" OR inurl:"gov")
```

--- 

## 💰 DORKS: Restituição do Imposto de Renda (IRPF)

6. 🔍 **Golpes usando promessa de restituição**

Busca páginas que prometem restituição do IRPF e solicitam dados sensíveis.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"restituição IRPF" OR intext:"restituição imposto de renda" OR intext:"consultar IRPF") (intext:"CPF" OR intext:"confirme seus dados" OR intext:"login")
```

7. 🔒 **Clones de portais do governo**

Procura páginas que tentam se passar por portais oficiais do governo, Receita Federal ou IRPF, pedindo CPF ou senha.

```plaintext
(site:vercel.app OR site:lovable.site) (inurl:"gov" OR inurl:"receita" OR inurl:"irpf") (intext:"CPF" OR intext:"senha")
```

8. 📧 **Phishing com links de confirmação de restituição**

Encontra páginas que simulam mensagens de confirmação de restituição, solicitando validação de dados.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"sua restituição foi liberada" OR intext:"confirme seus dados para receber" OR intext:"valide seu CPF")
```

9. 🏦 **Solicitação de atualização cadastral para IRPF**

Busca páginas que pedem atualização de cadastro para liberar restituição, um golpe comum em época de imposto de renda.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"atualize seu cadastro" OR intext:"regularize sua situação" OR intext:"pendência no IRPF") (intext:"CPF" OR intext:"senha")
```

---

## 🛍️ DORKS: Vendas fraudulentas de produtos populares

10. 🧴 **Falsos sites de venda Tupperware, Avon, Natura, etc.**

Procura páginas que usam marcas populares para atrair vítimas com promoções falsas.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"Tupperware" OR intext:"Avon" OR intext:"Natura" OR intext:"Jequiti") (intext:"promoção" OR intext:"desconto" OR intext:"compre agora")
```

11. 💳 **Captura de dados de pagamento (phishing de loja)**

Busca páginas que tentam capturar dados de cartão de crédito ou pagamento, usando marcas conhecidas.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"cartão de crédito" OR intext:"dados de pagamento" OR intext:"finalize sua compra") (intext:"Avon" OR intext:"Natura")
```

12. 🛒 **Falsas lojas com aparência legítima**

Procura páginas que simulam lojas oficiais, usando termos como "loja oficial" e métodos de pagamento populares.

```plaintext
(site:vercel.app OR site:lovable.site) (intitle:"loja oficial" OR inurl:"loja" OR inurl:"produtos") (intext:"Tupperware" OR intext:"Avon" OR intext:"Natura") (intext:"boleto" OR intext:"pix")
```

13. 📦 **Promoções falsas de frete grátis ou entrega expressa**

Busca páginas que prometem frete grátis ou entrega rápida para enganar consumidores.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"frete grátis" OR intext:"entrega expressa" OR intext:"envio imediato") (intext:"promoção" OR intext:"compre agora")
```

14. 🎣 **Dork combinada – golpe via IRPF ou loja falsa**

Procura páginas que misturam temas de restituição e promoções para capturar dados bancários ou pessoais.

```plaintext
(site:vercel.app OR site:lovable.site) (intext:"restituição" OR intext:"promoção" OR intext:"compre com desconto") (intext:"CPF" OR intext:"dados bancários")
``` 
Contribua adicionando novas dorks! 🔥

---

## 🤝 Como Contribuir

1. Faça um **fork** deste repositório.
2. Adicione suas dorks seguindo o padrão acima.
3. Envie um **Pull Request** com suas sugestões.
4. Sinta-se à vontade para sugerir melhorias no README ou na organização do repositório!

---

## ⚠️ Aviso Legal

> Este repositório é destinado **exclusivamente para fins educacionais e de pesquisa em segurança**. Não incentive ou realize atividades ilegais. Sempre reporte sites maliciosos às autoridades e aos provedores de hospedagem.

---

## 💬 Contato

Dúvidas, sugestões ou parcerias? Abra uma issue ou entre em contato!

---

Feito com 💙 para a comunidade de segurança. 

---

