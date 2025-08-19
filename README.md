# 🎤💬 Análise de Sentimentos com Azure Speech e Language Studio

Projeto realizado no desafio da DIO para praticar **IA no Azure**, utilizando:
- **Azure Speech Studio** (transcrição de fala para texto)
- **Language Studio** (análise de sentimentos e opiniões)

  ## Link dos sites:

  * (https://speech.microsoft.com/portal)
  * (https://ai.azure.com/)
  * (https://language.cognitive.azure.com/home)

---

## 📌 1. Transcrição de Áudio (Speech Studio)

Acessamos o **Azure Speech Studio** e utilizamos a ferramenta de transcrição.  
Configuração inicial: colocamos o audio que queremos que seja transcrito para texto.

![Configuração Speech Studio](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/speech-config.png)  

Execução do teste com o áudio: Eu escolhi uma musica qualquer, no idioma Inglês. E depois de 
ter analisando o audio, o resultado da tradução:

![Execução da transcrição](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/speech-execucao_resultado.png)  

depois de ter analisado guardamos a tradução, para usar no **Linguage Studio**

---

## 📌 2. Criando Recurso de Linguagem no Azure

No **Portal do Azure**, criamos o recurso de **Language Service**:  Antes disso temos que escolher o serviço de IA e Machine Learning.

![Criando recurso](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/azure-criar-recurso.png)  

Configuração do recurso:  

![Configuração](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/azure-config.png)  

Agora clicamos no botão de criar.

Confirmação de criação:  Agora temos que selecionar o nome do recurso que criamos no **Azure Speech**, depois colocamos a região, nome, e preço. 

![Recurso criado](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/azure-config-idioma-pre%C3%A7o.png)  

agora e so clicar no botla de examinar e criar.

Resultado da Criação do Recurso de **Language Studio**: Depois de ter criado esse recurso, vamos para o (https://language.cognitive.azure.com/home)

![Recurso criado](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/azure-confimacao-pronto.png)  

---

## 📌 3. Análise de Sentimento (Language Studio)

Com o recurso criado, usamos o **Language Studio**: Agora colocamos o texto transcrito pelo **Azure Speech Studio**, para analisar o texto dizer o sentimentos que estão sendo emitidos.

![Configuração da análise](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/language-config.png)  

Rodando a análise:  

![Execução](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/language-run.png)  
![Execução](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/language-run2.png)  
![Execução](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/languge-run3.png)  

Resultados obtidos:  

![Resultados](https://github.com/marcoA204/Azure-Speech-Language-Studio/blob/main/imagens/language-analytic-sentimentos.png)  

---

## ✅ Conclusão

- O **Speech Studio** permitiu converter áudio em texto.  
- O **Language Studio** classificou as frases em **positivo, negativo ou neutro**.  
- Ferramentas simples de usar e aplicáveis em **NLP e análise de feedbacks**.  
