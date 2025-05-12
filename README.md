# 💬 Microsoft Azure AI — Speech Studio & Language Studio (DIO Bootcamp)

Este repositório documenta minha experiência prática com as ferramentas **Azure Speech Studio** e **Language Studio**, como parte do laboratório proposto no bootcamp da DIO. O objetivo principal foi aplicar conceitos de inteligência artificial voltados à **análise de fala** e **linguagem natural**, utilizando serviços da plataforma Microsoft Azure.

---

## 🎯 Objetivos do Projeto

- Explorar o **Speech Studio** para transcrição de áudio em tempo real.
- Utilizar o **Language Studio** para análise de sentimento e estruturação de opiniões em texto.
- Documentar a experiência com capturas de tela e anotações técnicas.
- Praticar o uso do GitHub como repositório técnico.

---

## 🧠 Tecnologias Utilizadas

- **Microsoft Azure AI**
  - Speech Studio
  - Language Studio
- **GitHub**
- **Markdown**
- **WAV Audio File** para testes de transcrição
- Texto crítico musical (Haim – *Women in Music Pt. III*) para mineração de sentimento

---

## 🗣️ Speech Studio — Real-time Speech to Text

1. Criei uma **Speech Resource** no Azure com a região `East US` e nome `conversao-fala-texto`.
2. Gravei um áudio diretamente na plataforma com a seguinte fala:

   ```
   Hi everyone, my name is Theodoro. I am 36 years old. I live in Brazil and I teach English since 2012.
   ```

3. O resultado gerado foi uma transcrição precisa, exibida na interface com os metadados configurados para:
   - Idioma: English (US)
   - Speaker diarization: Off
   - Output format: Detailed

📷 *Capturas disponíveis na pasta* `/images/speech_studio/`

---

## 🧾 Language Studio — Sentiment and Opinion Mining

1. Acesse o recurso `language-resource-experimento` na região `Brazil South`.
2. Copiei um trecho de crítica musical sobre o álbum *Women in Music Pt. III* da banda HAIM.
3. Com a opção "Enable opinion mining" ativada, os resultados revelaram:
   - Sentimento do documento: **Misto**, com 57% positivo.
   - Sentenças específicas com **100% positivo**, principalmente nos trechos sobre "songwriting" e "curiosity".
   - Visualização clara das **opiniões associadas a palavras-chave** como “intimate”, “multidimensional”, “wide-ranging”, etc.

📷 *Capturas disponíveis na pasta* `/images/language_studio/`

---

## 📂 Organização do Repositório

```bash
📁 azure-ai-speech-language
├── README.md
├── /images
│   ├── speech_studio/
│   │   ├── azure_ai_real-time_speech_to_text1.png
│   │   ├── azure_ai_real-time_speech_to_text2.png
│   │   └── azure_ai_real-time_speech_to_text3.png
│   └── language_studio/
│       ├── language_studio1.png
│       ├── language_studio2.png
│       ├── language_studio3.png
│       ├── language_studio4.png
│       └── language_studio5.png
```

---

## ✅ Conclusão

Essa prática reforçou meu entendimento prático sobre os recursos de IA da Microsoft voltados para fala e linguagem, e como essas tecnologias podem ser aplicadas em contextos reais de ensino, análise textual e desenvolvimento de soluções com foco em linguagem natural.

---

## 🔗 Recursos

- [Documentação oficial do Speech Studio](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Documentação do Language Studio](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Guia GitHub Markdown](https://guides.github.com/features/mastering-markdown/)
- [Formação GitHub Certification (GitBook)](https://dio.me)