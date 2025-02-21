# Copiloto com Fluxo de Conversa Personalizado ✨

## Descrição 🎯
Este projeto demonstra como criar um copiloto com fluxo de conversa personalizado no **Microsoft Copilot Studio**. O objetivo é proporcionar uma experiência interativa de **agendamento de compromissos**.

## Fluxo de Conversa 💬
O fluxo de conversa para agendamento segue os seguintes passos:
1. **Usuário**: "Quero agendar uma reunião."
2. **Copiloto**: "Claro! Qual data você prefere?"
3. **Usuário**: "Quinta-feira, às 15h."
4. **Copiloto**: "Perfeito! Vou agendar para quinta-feira, 15h. Posso adicionar mais detalhes?"
5. **Usuário**: "Sim, é sobre o projeto X."
6. **Copiloto**: "Reunião agendada para quinta-feira, 15h, sobre o projeto X. Está tudo certo?"

## Aprendizado 🧠
Durante o desenvolvimento deste copiloto, aprendi que:
- O **Microsoft Copilot Studio** é uma ferramenta poderosa para criar fluxos de conversa interativos de forma simples.
- É possível personalizar as **intenções** e as **respostas automáticas**, oferecendo uma experiência rica ao usuário.
- A plataforma permite integração com **APIs externas**, como calendários, para agendamento de reuniões.

## Como Rodar o Projeto 🚀

1. **Pré-requisitos**:
   - Acesso ao **Microsoft Copilot Studio**.
   - Conta na **plataforma** para implementar o fluxo de conversa.

2. **Passos para Implementação**:
   - **1.** Acesse o [Microsoft Copilot Studio](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/).
   - **2.** Crie um novo projeto e utilize o exemplo de fluxo de conversa descrito no arquivo `fluxo_conversa.json`.
   - **3.** Adapte o fluxo conforme necessário, como personalizar as mensagens ou integrar com seu calendário.
   - **4.** Salve e teste o fluxo para garantir que o copiloto está funcionando corretamente.

3. **Testando o Fluxo**:
   - Após a criação, você pode testar o fluxo de conversa diretamente no **Copilot Studio**.
   - Basta interagir com o copiloto, como se fosse um usuário, para verificar a precisão do agendamento.

## Exemplo de Código 👨‍💻
Aqui está um exemplo simples de como configurar a interação para agendamento:

```json
{
  "intent": "Agendamento",
  "utterance": "Quero agendar uma reunião",
  "response": "Qual data você prefere para a reunião?"
}
