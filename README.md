# AIE — Suporte Conversacional e Regulação Emocional frente à Emergência Climática 🤖🌱

O **AIE** é uma tecnologia social e conversacional de código aberto desenvolvida para democratizar o conhecimento ambiental e oferecer suporte primário de autorregulação emocional diante da ansiedade climática, com foco em territórios vulneráveis e periferias urbanas brasileiras. 

Projeto submetido ao programa **AI4GOOD (Brazil Conference at Harvard & MIT)** e alinhado aos **ODS 3, 11 e 13**.

---

## 🧭 Funcionalidades Centrais

1. **Quero conversar (Acolhimento e Autorregulação):** Assistente virtual integrada à Gemini API para suporte em momentos de tensão (tempestades severas, deslizamentos, ondas de calor), com exercícios rápidos de respiração e autoproteção.
2. **Acesso rápido (Segurança e Utilidade Pública):** Consulta em tempo real da previsão do tempo via API Open-Meteo e acesso direto a contatos de emergência e Defesa Civil.
3. **Tirar dúvidas (Democratização Científica):** Assistente didática que traduz jargões ambientais e legislações em impactos práticos do cotidiano, combatendo o sensacionalismo.

---

## 🛠️ Pilha Tecnológica

* **Fluxo Conversacional:** Typebot (JSON)
* **Inteligência Artificial:** Google Gemini API (Google AI for Developers)
* **Dados Climáticos:** Open-Meteo API
* **Hospedagem & Mensageria:** Netlify e WhatsApp (Meta for Developers)

---

## 🔒 Privacidade e LGPD

* **Anonimato Garantido:** Nenhuma conversa ou relato individual é armazenado.
* **Dados Restritos:** Registro apenas de métricas territoriais e climáticas agregadas para mapeamento de áreas de vulnerabilidade.
* **Responsabilidade Ética:** O bot atua estritamente em acolhimento primário e psicoeducação, recomendando a busca de atendimento especializado na rede pública (SUS).

---

## 📥 Como importar o fluxo no Typebot

1. Baixe o arquivo `typebot-export-aie-06z6dq9.json` deste repositório.
2. Acesse seu painel no [Typebot](https://typebot.io/).
3. Crie um novo Typebot ou abra um fluxo existente.
4. Clique no menu de configurações do fluxo e selecione a opção **Import** (Importar).
5. Selecione o arquivo `.json` baixado e configure suas chaves de API nos blocos de integração.

---

## 📄 Licença

Distribuído sob licença aberta [MIT](https://opensource.org/licenses/MIT) para uso e replicação comunitária.
