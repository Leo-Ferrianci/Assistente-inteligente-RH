# 📢 Copiloto de RH - Assistente de Comunicação Interna

> Uma solução de IA Generativa para agilizar a comunicação corporativa e desobstruir demandas do RH.

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-brightgreen) ![Tech](https://img.shields.io/badge/AI-Google%20Gemini-blue)

## 🎯 O Desafio
Este projeto foi desenvolvido como parte de uma atividade acadêmica para solucionar um problema real: **a sobrecarga do departamento de RH com comunicações repetitivas.**

A missão foi prototipar um assistente inteligente capaz de transformar *inputs* brutos e informais em comunicados corporativos assertivos, empáticos e bem formatados para diferentes canais (E-mail e WhatsApp).

## 🧠 Engenharia de Prompt (Técnicas Utilizadas)
Para garantir a qualidade e consistência das respostas, foram aplicadas técnicas avançadas de Prompt Engineering nas instruções do sistema:

* **Role Prompting:** A IA assume a persona de um "Especialista Sênior em Comunicação Interna", garantindo tom profissional e empático.
* **Chain of Thought (Cadeia de Pensamento):** O modelo é instruído a analisar a urgência, o tom e o público-alvo *antes* de escrever o texto final.
* **Few-Shot Prompting:** Foram fornecidos exemplos práticos (treinamento) de entradas e saídas ideais para padronizar o formato da resposta.

## 🚀 Como Utilizar

Você pode testar a ferramenta diretamente pelo navegador ou configurar seu próprio ambiente.

### 🔗 Acesso Rápido (Live Demo)
Acesse o chat configurado e pronto para uso através do link:
👉 **[Clique aqui para acessar o Copiloto de RH no Gemini](https://gemini.google.com/share/b38f73e4ddac)**

### 📝 Instruções de Uso
1.  Abra o link acima.
2.  No campo de chat, digite as informações "brutas" do comunicado (tópicos, datas, avisos rápidos).
3.  A IA irá processar e devolver o texto formatado para E-mail e/ou WhatsApp.

#### Exemplos de Comandos (Prompts):
* **Aviso de Feriado:** *"Avisar que o escritório estará fechado no feriado do dia 12. Retornamos dia 13."*
* **Convite de Evento:** *"Festa de fim de ano dia 20/12 às 19h no salão de festas. Precisa confirmar presença até dia 15."*
* **Cobrança Amigável:** *"Lembrar os gestores de enviarem as avaliações de desempenho até sexta-feira."*

## 📸 Exemplo Prático

**Entrada do Usuário:**
> "Avisar que a festa de fim de ano é dia 20/12 as 19h. Precisa confirmar presença até dia 15."

**Saída do Assistente (Opção WhatsApp):**
> **✨ NOSSA FESTA DE FIM DE ANO ESTÁ CHEGANDO! ✨**
>
> Pessoal, anotem na agenda para não ficarem de fora da nossa celebração:
>
> 📅 **Quando:** 20/12 (Sexta-feira)
> ⏰ **Horário:** 19h
> 📍 **Onde:** [Inserir Local]
>
> ⚠️ **IMPORTANTE:** Precisamos da sua confirmação de presença até o dia 15/12.

## ⚠️ Limitações
* A ferramenta foca apenas em textos corporativos internos (endomarketing).
* Não deve ser utilizada para redação de documentos jurídicos ou contratuais complexos.
* Sempre revise os dados sensíveis (datas e locais) antes de enviar.

---
*Projeto desenvolvido para a disciplina de Inteligência Artificial / Prompt Engineering.*
