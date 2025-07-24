# 📝 Atividades Práticas – Dia 1

## 🔹 1. Situação: QA em um app de delivery

**Requisito analisado:**  
“O cliente deve receber uma notificação quando o pedido sair para entrega.”

**Pergunta crítica levantada pelo QA:**  
E se o app estiver offline? A notificação será reemitida depois?

**Caso de Teste elaborado:**  
- Título: Verificar reenvio de notificação após pedido sair para entrega com app offline
- Pré-condição: App deve estar desconectado da internet
- Passos:
  1. Fazer um pedido
  2. Colocar o app em modo offline
  3. Marcar o pedido como "saiu para entrega"
  4. Reativar a internet
- Resultado esperado: O app deve exibir a notificação pendente

---

## 🔹 2. Diferença entre QA e Testador na prática

**Cenário:** Teste de login em app de delivery

- O QA pergunta: O sistema está validando senhas com criptografia? Há bloqueio após 3 tentativas?
- O Testador: Simula login com dados inválidos e registra se o sistema responde corretamente

---

## 🔹 3. SDLC na prática (exemplo do app de delivery)

- **Requisito**: Ter login e mapa do entregador
- **Análise**: Que tecnologia usar? Firebase para autenticação?
- **Design**: Layout do login e visualização do mapa
- **Implementação**: Desenvolvedores criam a tela
- **Teste**: QA cria casos de login válido, inválido, senha errada etc.
- **Deploy**: App na Play Store
- **Manutenção**: Corrigir bugs relatados pelos usuários

---

## 🔹 4. STLC na prática (login com bloqueio)

- **Análise**: "Deve bloquear login após 3 tentativas erradas?"
- **Planejamento**: Tipo de teste: funcional; responsável: QA
- **Criação de Caso de Teste**: "Login com senha errada 3x"
- **Ambiente**: App instalado, conta de teste criada
- **Execução**: Realiza tentativas erradas, valida o bloqueio
- **Relatório**: “Bug: não houve bloqueio após 3 tentativas – incluir print”
- **Encerramento**: Após correção, retestar e encerrar

---

## ✅ Conclusão prática

Hoje vimos como o QA participa ativamente desde o início do projeto, previne erros com perguntas inteligentes e transforma requisitos em testes concretos.  
A prática de levantar dúvidas e criar cenários é essencial para garantir qualidade real no produto final.
