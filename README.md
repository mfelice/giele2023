# Herramientas de inteligencia artificial para la práctica y evaluación de idiomas

## Introducción

### Ejercicios interactivos
www.menti.com

## Modelos de lenguaje

### Tarea
**Crear un ejercicio para rellenar espacios en blanco a partir del siguiente texto. Usar un modelo de lenguaje para identificar palabras óptimas para eliminar.**

Francisco era un niño apasionado por el ajedrez desde pequeño. Un día, mientras jugaba en la plaza, conoció a un gran maestro que lo vio jugar y decidió tomarlo bajo su cuidado. Con sus enseñanzas, Francisco rápidamente mejoró sus habilidades y pronto se convirtió en un famoso jugador de ajedrez. A medida que crecía, Francisco ganó varios torneos importantes y se estableció como uno de los mejores jugadores de España. Su talento natural y dedicación al juego hicieron que fuera considerado uno de los grandes maestros de ajedrez de todos los tiempos.


### BERT
Español: https://huggingface.co/dccuchile/bert-base-spanish-wwm-cased  
Multilingüe: https://huggingface.co/xlm-roberta-large  
Inglés: 
https://huggingface.co/spaces/UserConfused/bert-base-uncased  
https://huggingface.co/bert-base-uncased  
https://huggingface.co/bert-large-uncased  

### Predictores de palabras basados en GTP-2 (inglés)
https://demo.allennlp.org/next-token-lm  
https://huggingface.co/spaces/Bhagu69/next-word-fun  

### Predictores de palabras basados en n-gramas (inglés) 
https://fschoen.shinyapps.io/NextWordPrediction/  
https://philferriere.shinyapps.io/WordPredictR/

## Evaluación automática de textos
### Tarea I

### Tarea II
**Determinar manualmente el nivel MCER del siguiente texto escrito por un estudiante de español**

Nací en Asia y viví mucho tiempo allí en varios países, pero como mis padres son británicos, al cabo de unos años terminamos en Escocia, país natal de mi padre. Siempre he querido volver a Asia a visitar los sitios en donde pasé mi niñez y tuve la oportunidad hace unos años de hacerlo. Habían invitado a mi marido a dar una charla en una universidad en Tailandia, así que, sin más, aceptamos la invitación y nos fuimos. De camino a Tailandia pasamos por Malasia, donde había vivido cuatro años. Avisamos al director de la finca donde había trabajado mi padre de nuestra llegada y nos dirigimos allí. Cuando vivía en Malasia la finca era una plantación de té, mezclado con algunos árboles de goma para dar sombra. Ya solo cultivaban los árboles de goma y los labradores ya no eran indios y chinos, como en mi día, sino gente de Indonesia y Filipinas. El director fue increíblemente amable y nos llevó a mi antigua casa. Era obvio que habían cortado el césped aquel día y se habían molestado mucho en preparar la casa para nuestra visita. Me asombraba que estaba exactamente como cuando vivía en ella hacía 35 años, incluso tenía las mismas cortinas y algunos de los muebles eran los mismos. Entramos en una habitación que anteriormente había sido el despacho de mi padre. No habían tenido tiempo de limpiarlo y estaba llena de telarañas, y casi impenetrable. La casa estaba abandonada, ya que no había tanta personal como en el día de mi padre, y el nuevo director vivía en otra casa en la finca.
### Write&Improve (inglés)
https://writeandimprove.com/workbooks#/wi-workbooks

## Corrección gramatical

### Task
**Corregir el siguiente texto:**

My favourite season of the year is summer. I think that most of the people love summer, especially the people in Greece. I dont know why but the summer it is the most beautiful season.  
I live in Greece, and especially in an island, so I know very well what summer means. It means swimming at the wonderfull beaches, tasting the delicious foods ad having wonderful time every day and every night with your friends.  
I think that the summer makes people to feel great, to have fun, to enjoy themselves. I believe that the summer is a season for everybody who wants to have wonderful time and wonderful memories wherever the go.  

### Correctores gramaticales
Español:
https://spanishchecker.com/es/ 
https://abccorrector.com/corrector-castellano.html  
https://lorcaeditor.com/  
Multilingües: 
**LanguageTool:** https://languagetool.org/  
**Reverso:** https://www.reverso.net/ortografia/
**Zoho:** https://www.zoho.com/es-xl/writer/free-grammar-checker.html  
Inglés:
**Grammarly:** https://www.grammarly.com/grammar-check  
**QuillBot:** https://quillbot.com/grammar-check  
**Ginger:** https://www.gingersoftware.com/grammarcheck  
**Writer:** https://writer.com/grammar-checker/  

### ERRANT
https://nlptoolbox.cl.cam.ac.uk/errant/

## Automatic speech recognition
**Task**
1. Listen to the following audio clip and manually transcribe what you hear.
2. Use an ASR service to generate an automatic transcription of the audio.
3. Compare both transcriptions and compute a word error rate (WER).

https://github.com/mfelice/giele2023/assets/11545607/28139b7e-3a8d-4adf-9887-e7cd35330aae

### Servicios de reconocimiento de voz
**OpenAI Whisper:** https://replicate.com/openai/whisper  
**AssemblyAI:** https://www.assemblyai.com/playground/source  
**VoiceGain:** https://demo.voicegain.ai/  

### Calculadora WER
https://www.amberscript.com/en/wer-tool/

## Speech synthesis (text to speech)
### Task
Create a listening comprehension question consisting of a dialogue between three people with different accents.

1. Create a short dialogue and question.
2. Create an audio file for each turn of the conversation using a TTS service.
3. Join all the audio files together.

**Sample dialogue**  
Ani is from Kenya, Ben is from the UK and Chaya is from India.  

**1-A:** Hi guys, how are you doing?  
**2-B:** Hi Ani, not bad, thanks.  
**3-C:** Yeah, all good. How about you?  
**4-A:** A bit stressed to be honest... I've got my driving test today.  
**5-B:** Really? I thought it was next week!  
**6-A:** It was, but they changed it.  
**7-C:** That's unfortunate. But you've practised a lot, I'm sure you'll pass!  
**8-A:** I hope so!  

**Question**  
Ani is going to take a driving test. Why is she stressed about it?

a) She hasn't practised much.  
b) Her test has been postponed until next week.  
d) Her test is today.  
c) She is not confident she will pass.  

### TTS services
https://ttsfree.com/  
https://ttsmp3.com/  
https://ttstool.com/  
https://huggingface.co/spaces/elevenlabs/tts  
https://freetools.textmagic.com/text-to-speech  
https://speechgen.io/

### Audio joiner
https://audio-joiner.com/

## Large language models

### LLMs
**ChatGPT:** https://chat.openai.com/  
**Bing Chat (GPT-4):** https://www.microsoft.com/en-us/edge/launch/bing-chat-features?form=MT00IR  
**ChatGPT (no registration, unofficial):** https://chat.chatgptdemo.net/ https://talkai.info/chat/  
**Llama 2:** https://labs.perplexity.ai/ https://www.llama2.space/  
**Claude:** https://claude.ai/  

### Task I
Can you guess who wrote these texts?
A human or a machine?

**Passsage 1**  
Every country in the world suffers environmental catastrophes. This is a natural consequence of the struggle between development and environment. If a country decided to live isolated from the rest of the world, living on what it can naturally grow and produce, it surely wouldn’t be highly polluted. But we all want exotic food and technological items from all over the world, so we have to pay the price. Investing on electrical transport would benefit the environment a lot. Even more if this electricity came from a natural source of energy like wind, rivers and solar boards. We also have to take care of our rivers and seas. We all have heard about factories throwing highly toxic substances to rivers, without minimizing their poisoning effects. A really strict law should be applied to fine these factories and make them change their policy.

**Passsage 2**  
Global warming is a serious issue that affects the entire planet. The Earth's temperature is rising because of human activities. When we burn fossil fuels like coal, oil, and gas, harmful gases are released into the atmosphere. These gases trap heat from the sun and cause the Earth to become warmer. This leads to various problems such as melting ice caps, rising sea levels, and extreme weather events. It is important to reduce our carbon footprint by using less energy and finding cleaner sources of power. We can also make a difference by recycling, conserving water, and protecting natural habitats. Taking action against global warming is crucial for the well-being of our planet and future generations.

**Passsage 3**  
Society has a responsibility to take care of the environment. We all live on this planet, so it's important for us to do our part to keep it clean and healthy. There are many things we can do to be environmentally responsible. We should recycle our waste, such as paper, plastic, and cans, instead of throwing them away. It's also important to save energy by turning off lights and appliances when we're not using them. Using public transportation or carpooling can help reduce pollution from cars. We should also avoid wasting water and try to conserve it. Planting trees and taking part in community clean-up activities are great ways to contribute to a cleaner environment. By being environmentally responsible, we can make a positive impact on our planet and ensure a better future for ourselves and future generations.

### AI content detectors
https://gptzero.me/  
https://writer.com/ai-content-detector/  
https://platform.openai.com/ai-text-classifier  
https://contentatscale.ai/ai-content-detector/  
https://www.wordtune.com/ai-content-detector  
https://undetectable.ai/  
https://originality.ai/ (paid)  

### Task II

Can you “humanise” the following AI-generated text?
Can we fool detectors?

**The Importance of Art**

Art is a vital part of human life. It offers many benefits to individuals and society as a whole. One of art's most important roles is as a universal language that can bridge cultural gaps and foster understanding among diverse communities. Art also provides a unique way to express emotions and explore oneself.

In education, art can enhance cognitive development, creativity, and problemsolving skills. It can also beautify our surroundings and instill a sense of pride and cultural identity within communities. Furthermore, art can challenge societal norms and encourage critical thinking, making it a catalyst for social change and progress.

In essence, art is more than just a form of entertainment; it is a powerful tool that can enrich lives, promote empathy, and nurture creativity. By embracing art in all its forms, we can enhance our collective human experience and create a more vibrant and culturally rich society.

### AI text "humanisers"
https://undetectable.ai/ (paid)  


## Text to image

### Task
Using an LLM, experiment with different prompts to perform the tasks in the previous slide.
How would you rate the quality of the output?
How much effort does it take to achieve the desired results?

### Task
Can you write a prompt to generate an image like this one?  

![picture](https://github.com/mfelice/ndea2023/assets/11545607/aadd2fe3-9ad6-4c3c-b5a1-41d090ad45a1)

### AI image generators
**DALL·E 2:** https://labs.openai.com/  
**Stable Diffusion:** https://stablediffusionweb.com/#demo https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0 https://huggingface.co/spaces/songweig/rich-text-to-image  
**Openjourney 4:** https://huggingface.co/prompthero/openjourney-v4  
