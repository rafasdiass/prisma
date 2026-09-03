# Prisma, por Ayla

Protótipo de interface para um assistente de IA de observação multimodal aplicado à avaliação psiquiátrica. É a Ayla numa aplicação clínica específica.

**Demo ao vivo:** https://rafasdiass.github.io/prisma/

## O que é

O Prisma decompõe o que a pessoa mostra numa entrevista clínica — fala, voz, vídeo, comportamento — em vários sinais, e devolve esse espectro para o médico ler. Conduzido junto com o profissional, ele roda uma entrevista transdiagnóstica multimodal e devolve um mapa de padrões e divergências para o médico interpretar. Ele não diagnostica: mede compatibilidade de padrão, mostra evidência com marca de tempo, e para quando há sinal de risco.

O protocolo por trás do produto combina três referências públicas, sem reproduzir nenhuma na íntegra:

- **DSM-5-TR Level 1 Cross-Cutting Symptom Measure** (APA) — varredura de 13 domínios psiquiátricos
- **Exame do Estado Mental** — observação estruturada de aparência, fala, humor/afeto, pensamento, percepção e cognição
- **mhGAP** (OMS) — lógica de avaliação e encaminhamento por apresentação clínica

## Duas lentes, um mesmo protocolo

O produto atende dois públicos diferentes sobre a mesma base de 13 domínios:

- **Consulta** — dashboard para a psiquiatra revisar uma sessão gravada: parecer integrado da Ayla, padrões ranqueados, microexpressões, voz e prosódia, psicomotricidade, padrões relacionais e divergências entre relato e comportamento.
- **Estudo** — workspace para o aluno de Psicologia praticar o raciocínio de tradução domínio clínico → sinal computável → extractor, com um analisador funcional de texto para testar hipóteses.

## Status

**Piloto em fase de validação.** Este repositório contém um protótipo de interface (HTML/CSS/JS estático, sem backend) para uso em conversas de produto e numa demonstração científica em congresso de Psicologia/Psiquiatria. Nenhum dado real de paciente é processado aqui — todos os valores exibidos são ilustrativos.

O protocolo clínico foi desenhado pela Dra. Ana Lívia, psiquiatra, que conduz as entrevistas do piloto e assina a validação clínica dos achados.

## Origem

Parte da parceria de pesquisa entre a **UniAteneu** e a **LaVita Code**, dentro da extensão *Mentes Artificiais*.

---

Nenhuma decisão diagnóstica é tomada por este sistema. A conclusão clínica é sempre do profissional responsável.
