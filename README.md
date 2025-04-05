# Language-Studio-Azure-AI-DIO
Desafio DIO Análise de Sentimentos com Language Studio (Speech Studio) no Azure AI

## Speech Studio  
Processamento de áudio, incluindo reconhecimento de voz e conversão de discurso em texto, facilitando a análise e compreensão de informações transmitidas por meio de áudio.
![image](https://github.com/user-attachments/assets/d06bb184-6db6-4d19-9ae2-60870ab52188)


## Language Studio  
Processamento de linguagem natural, incluindo análise de texto, tradução automática, detecção de idioma e extração de insights linguísticos, auxiliando na compreensão e interação com conteúdo textual em diferentes idiomas.

### Criação do recurso
![image](https://github.com/user-attachments/assets/5dd57c98-3bc1-4d1c-b0c6-d748d603a1de)

![image](https://github.com/user-attachments/assets/cf891d30-f96e-42be-bb6e-d032e3537547)

![image](https://github.com/user-attachments/assets/a2a28376-0386-47ae-86e6-1f31e431873b)

Os resultados das análises realizadas pelo Speech Studio e Language Studio podem ser visualizados em formato JSON, facilitando a integração com outros sistemas e a manipulação de dados.

```json
{
    "documents": [
        {
            "id": "id__941",
            "sentiment": "mixed",
            "confidenceScores": {
                "positive": 0.23,
                "neutral": 0.01,
                "negative": 0.76
            },
            "sentences": [
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 0,
                    "length": 64,
                    "text": "Hoje foi um daqueles dias que começam mal e pioram com o tempo. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "positive",
                    "confidenceScores": {
                        "positive": 0.86,
                        "neutral": 0,
                        "negative": 0.14
                    },
                    "offset": 64,
                    "length": 103,
                    "text": "Perdi o ônibus logo cedo, levei uma bronca no trabalho e ainda derramei café na minha camisa favorita. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0.06,
                        "neutral": 0.05,
                        "negative": 0.89
                    },
                    "offset": 167,
                    "length": 121,
                    "text": "No entanto, no fim da tarde, um amigo me ligou do nada só pra dizer que estava com saudades, e isso aqueceu meu coração. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "neutral",
                    "confidenceScores": {
                        "positive": 0.04,
                        "neutral": 0.96,
                        "negative": 0
                    },
                    "offset": 288,
                    "length": 78,
                    "text": "Caminhei um pouco ao ar livre e finalmente consegui respirar com mais leveza. ",
                    "targets": [],
                    "assessments": []
                },
                {
                    "sentiment": "negative",
                    "confidenceScores": {
                        "positive": 0,
                        "neutral": 0,
                        "negative": 1
                    },
                    "offset": 366,
                    "length": 31,
                    "text": "Talvez nem tudo esteja perdido.",
                    "targets": [],
                    "assessments": []
                }
            ],
            "warnings": []
        }
    ],
    "errors": [],
    "modelVersion": "2025-01-01"
}
```
Documentação do Speech Studio: https://docs.microsoft.com/pt-br/azure/cognitive-services/speech-service/

Documentação do Language Studio: https://docs.microsoft.com/pt-br/azure/cognitive-services/text-analytics/
