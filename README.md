📘 Guia de Vacância – FUNPRESP-JUD

Aplicação web interativa desenvolvida para orientar participantes da **FUNPRESP-JUD** sobre seus **direitos, opções e institutos previdenciários** em casos de **vacância do cargo** ou **aposentadoria**, considerando o status do participante e o tempo de contribuição ao plano.

---

🎯 Objetivo

O **Guia de Vacância** tem como objetivo simplificar a tomada de decisão do participante, oferecendo:

- Identificação de **direito imediato ao benefício**
- Indicação dos **institutos disponíveis**
- Seleção automática do **Termo de Opção correto**
- Download do **PDF correspondente**
- Orientações claras sobre **próximos passos**

---

🧭 Fluxo da Aplicação

A aplicação funciona como um **assistente passo a passo (wizard)**:

1. **Status no plano**
   - Participante ativo
   - Inscrição cancelada

2. **Tipo de cessação do vínculo**
   - Vacância do cargo
   - Aposentadoria

3. **Tipo de aposentadoria** (quando aplicável)
   - Compulsória ou voluntária
   - Invalidez ou falecimento

4. **Tempo de contribuição**
   - Informado em meses completos

5. **Resultado**
   - Direito ao benefício **ou**
   - Lista de institutos disponíveis
   - Termo de Opção correto
   - Download do PDF
   - Canais de atendimento

---

## ⚙️ Tecnologias Utilizadas

- **HTML5** – Estrutura da página
- **CSS3** – Estilização avançada, animações e responsividade
- **JavaScript (Vanilla)** – Regras de negócio e controle do fluxo

> Não há uso de frameworks ou bibliotecas externas.

---

📂 Estrutura de Arquivos

```text
/
├── index.html              # Aplicação principal (HTML + CSS + JS)
├── logo.png                # Logotipo da FUNPRESP-JUD
├── /pdfs                   # PDFs dos Termos de Opção
│   ├── TERMO DE OPÇÃO - COMPLETO.pdf
│   ├── TERMO DE OPÇÃO - RESGATE.pdf
│   ├── TERMO DE OPÇÃO - AUTOPATROCÍNIO - RESGATE.pdf
│   ├── TERMO DE OPÇÃO - BPD - PORTABILIDADE - RESGATE.pdf
│   └── ...
