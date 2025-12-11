# HirePrep – Plataforma de Apoio para Entrevistas de Emprego 🎓💼

O **HirePrep** é um aplicativo instrucional desenvolvido para auxiliar jovens na preparação para entrevistas de emprego, especialmente estudantes do IFPR Campus Pinhais. A plataforma busca enfrentar a dificuldade de inserção juvenil no mercado de trabalho, marcada por altos índices de desemprego e falta de orientação profissional adequada, conforme apontado por pesquisas recentes (G1, 2024; O GLOBO, 2023) .

---

## 🎯 1. Objetivo do Projeto

De acordo com a documentação do TCC, o objetivo central do HirePrep é:

> Desenvolver um aplicativo instrucional voltado à preparação de jovens para entrevistas de emprego, analisando seu potencial na promoção de habilidades socioemocionais essenciais à empregabilidade .

Entre as habilidades socioemocionais destacadas estão:

* comunicação,
* inteligência emocional,
* resolução de problemas.

Essas competências são apontadas como cruciais por autores como Chiavenato (2004), Araújo (2012) e por pesquisas acadêmicas sobre soft skills presentes na fundamentação teórica do projeto .

---

## 🛠️ 2. Tecnologias Utilizadas

As tecnologias descritas na metodologia oficial do TCC foram:

### **Frontend** 📱

* React Native
* JavaScript
* CSS

### **Backend** ⚙️

* Node.js
* SQLite3

### **Ferramentas auxiliares**

* Insomnia (para testar a API)

---

## 📌 3. Funcionalidades Principais

De acordo com a seção **Funcionalidades (3.2)** e demais descrições oficiais do projeto:

### **🏠 Tela Inicial**

Acesso às principais áreas do app.

### **💡 Dicas**

Conteúdos teóricos sobre comunicação, inteligência emocional e comportamento profissional, com base na fundamentação teórica apresentada no TCC.

### **❓ Perguntas (Gerais e Simuladas)**

Inclui perguntas comportamentais, situacionais e técnicas, elaboradas com base em estudos sobre entrevistas de emprego.

### **📝 Quiz**

Quiz de múltipla escolha e questões dissertativas, sem necessidade de login, projetado para desenvolver soft skills como comunicação e gestão emocional.

### **ℹ️ Sobre Nós**

Explica o propósito do aplicativo e seu papel social.

---

## 🎯 4. Público-Alvo

Conforme o TCC:

* Estudantes do IFPR – Campus Pinhais
* Jovens entre 14 e 24 anos
* Pessoas com pouco acesso à orientação profissional
* Jovens em vulnerabilidade social

Essa delimitação surge do contexto de desemprego juvenil analisado na fundamentação teórica (G1, 2024; O GLOBO, 2023) .

---

## 🚀 5. Como Executar o Projeto

### **Frontend** 📱

```
npm install
npx expo start
```

### **Backend** ⚙️

```
npm install
node index.js
```

Requisitos citados na documentação: Node.js, ambiente mobile (Expo) e SQLite3 instalados no sistema para execução completa da aplicação .

---

## 📂 6. Estrutura Geral do Projeto

```
/hireprep
 ├── frontend/
 │    ├── assets/
 │    ├── src/
 │    │    ├── screens/
 │    │    ├── components/
 │    │    ├── services/
 │    │    ├── database/
 │    │    └── utils/
 │    └── App.js
 │
 ├── backend/
 │    ├── database/
 │    ├── controllers/
 │    ├── routes/
 │    ├── models/
 │    └── index.js
 │
 ├── package.json
 └── README.md
```

---

# 📚 7. Referências (extraídas diretamente do TCC)

* ARAÚJO, M. C. de. *Recrutamento e Seleção com Base em Competências*. 2012. 
* BASTOS, C. R. P. *Solução de problemas e tomadas de decisão em reuniões empresariais*. 2012. 
* BRASIL. *Lei nº 10.097/2000 – Lei da Aprendizagem*. 
* BRASIL. *Lei nº 11.892/2008 – Institutos Federais*. 
* CHIAVENATO, I. *Gestão de Pessoas*. 2014. 
* COUTINHO, T. *Comunicação Verbal e Não Verbal*. 2020. 
* G1. *Dificuldades dos jovens no primeiro emprego*. 2024. 
* O GLOBO. *Desemprego entre jovens é o dobro da média nacional*. 2023. 
* HANSEN et al. *Inteligência emocional e engajamento no trabalho*. 2018. 
* LIMA & TEIXEIRA. *Gestão de pessoas e direcionamento estratégico*. 2000. 
* LOPES & LIMA. *Linguagem corporal na entrevista de emprego*. 2023. 
* MATOS, G. G. *Comunicação empresarial sem complicação*. 2009. 
* OLIVEIRA et al. *Comunicação e inteligência emocional*. 2022. 
* PEREIRA DA SILVA & MORAIS XAVIER. *Tecnologias digitais e práticas de linguagem*. 2022. 
* TOMMASI & CORROCHANO. *Políticas de trabalho para jovens no Brasil*. 2020. 
