# Política de Privacidade — Numi

Última atualização: 28 de junho de 2026

Esta política explica quais dados o bot **Numi** coleta, para que servem e como você pode apagá-los.

## 1. Quais dados coletamos

| Dado | Para quê | Quando |
|---|---|---|
| Seu ID do Discord | Identificar sua conta e seu Numi | Ao mencionar o bot ou usar qualquer comando |
| Idioma (locale) | Responder no idioma certo | Detectado automaticamente, ou escolhido nas Configurações |
| Dados do seu Numi (nome, nível, EXP, status, itens, moedas) | Funcionamento do jogo | A cada ação (alimentar, banho, jogar, etc.) |
| Preferência de notificações | Saber se podemos te enviar DM | Configurações do bot |
| CPF/CNPJ | Exigido pelo provedor de pagamentos para emissão de cobrança, apenas se você comprar algo | No momento de uma compra/assinatura |
| Histórico de pagamentos (sem dados de cartão) | Liberar benefícios comprados e suporte a reembolsos | No momento de uma compra/assinatura |
| Eventos de uso anônimos (ex.: "comando executado", "Numi chocou") | Entender quais funcionalidades são usadas, melhorar o bot | Continuamente, via Mixpanel — sem conteúdo de mensagens |

Não lemos nem armazenamos o conteúdo de mensagens do servidor — só processamos a menção `@Numi` que abre o bot, e as interações de comandos/botões que você mesmo cria.

## 2. Onde os dados ficam

- Dados de jogo (Numi, moedas, itens): banco de dados próprio (PostgreSQL), hospedado pelo desenvolvedor.
- Pagamentos: processados pela Asaas (provedor de pagamentos terceiro); seguimos a política de privacidade deles para os dados que passam por lá.
- Eventos de uso: Mixpanel (se a coleta estiver habilitada).

## 3. Com quem compartilhamos

Não vendemos nem compartilhamos seus dados com terceiros para fins de marketing. Compartilhamos o mínimo necessário com:

- **Asaas** (processamento de pagamento), apenas se você fizer uma compra.
- **Mixpanel** (analytics de uso agregado, sem dados de pagamento ou CPF).

## 4. Como apagar seus dados

Em **Configurações → Deletar conta**, dentro do próprio bot, você pode apagar permanentemente sua conta, seu Numi e todo o progresso associado. A exclusão é imediata no nosso banco principal.

Por motivos de auditoria de fraude e chargeback de pagamentos, mantemos um backup temporário dos dados deletados por um período limitado. Para solicitar a remoção também desse backup, contate o desenvolvedor pelo servidor de suporte do Numi.

## 5. Seus direitos

Você pode, a qualquer momento:

- Ver seus dados atuais com `/numi status`.
- Mudar seu idioma e preferência de notificações nas Configurações.
- Apagar sua conta e dados (seção 4).

## 6. Contato

Dúvidas sobre privacidade ou pedidos relacionados aos seus dados: servidor de suporte do Numi ou mensagem direta ao desenvolvedor pelo Discord.

Veja também nossos [Termos de Serviço](./terms-of-service-pt.md).
