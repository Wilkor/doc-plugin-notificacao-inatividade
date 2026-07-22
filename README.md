![icone_github](https://github.com/Wilkor/doc-plugin-notificacao-inatividade/assets/34819624/bc272546-a8ca-49cf-a5f3-c997573b0bea)

# Como enviar alertas automáticos de inatividade para clientes no BlipDesk com Notificação de Inatividade

A extensão **Notificação de Inatividade** monitora chamados em atendimento humano no BlipDesk e envia réguas de até 3 mensagens de alerta automáticas para clientes que demoram a responder, encerrando o ticket caso a inatividade persista.

**Palavras-chave:** Notificação de Inatividade, Inatividade do Cliente, Alerta BlipDesk, Encerramento de Ticket, SLA de Resposta, Régua de Inatividade

---

### 1. Vídeo demonstrativo
Esta extensão não possui vídeos ainda.


### 2. Introdução
A extensão **Notificação de Inatividade** evita que atendentes fiquem com tickets travados aguardando respostas de clientes inativos. Ela automatiza o envio de cobranças amigáveis e realiza o encerramento do chamado se o cliente não interagir dentro do tempo estipulado.

### 3. Funcionalidades
A extensão **Notificação de Inatividade** oferece as seguintes funcionalidades:
- **Envio Sequencial de 3 Mensagens de Alerta**: Envio de mensagens personalizadas em intervalos configuráveis.
- **Encerramento Automático de Ticket**: Encerra o chamado caso o cliente não responda à última mensagem de alerta.
- **Integração com SLA do Desk**: Conexão com a configuração "Tempo máximo de resposta do cliente" do Blip.
- **Extensão Google Chrome**: Monitoramento nativo no navegador do atendente.

A extensão **Notificação de Inatividade** é suportada nos seguintes canais: **BlipDesk / Chrome Extension**.

### 4. Instalação e Configuração
Após ativar a extensão através da Blip Store, ela deve ser instalada no bot Router/Roteador.

#### Passo 1 — Configurar o tempo no chatbot de atendimento:
1. No Blip, acesse o chatbot onde fica o seu Atendimento Humano;
2. Vá em **Atendimento -> Configurações Gerais**;
3. Navegue até **Tempo máximo de resposta do cliente**;
4. Em tempo de primeiro alerta, defina em quantos minutos o cliente deve receber a mensagem quando estiver inativo:

![image](https://user-images.githubusercontent.com/34819624/199086067-e964ceaf-74c6-4489-aea8-b3934b9d3ea3.png)

#### Exemplo de Intervalo de Envio:
Se configurado para 1 minuto (para fins de teste/exemplo):
- **1º minuto**: Envia a primeira mensagem de alerta;
- **2º minuto**: Envia a segunda mensagem de alerta;
- **4º minuto**: Envia a última mensagem e encerra o ticket.

*OBS: Você pode configurar a quantidade de minutos da forma que desejar.*

#### Passo 2 — Configurar as 3 mensagens na extensão:
1. Abra a extensão **Notificação de inatividade** no Blip;
2. Selecione o chatbot de atendimento;
3. Cadastre as 3 mensagens que serão enviadas sequencialmente ao cliente inativo:

![image](https://user-images.githubusercontent.com/34819624/199088206-416deeca-015d-4e88-9929-594496d64164.png)

#### Passo 3 — Instalar no Google Chrome:
Instale a extensão no navegador Chrome de cada atendente através do link:  
https://chrome.google.com/webstore/detail/plugin-desk/bmjjlaomahkobdcmgnbihomlipaoolnh?hl=pt-BR

Após concluir os passos, o chatbot estará pronto para notificar e encerrar atendimentos ociosos.

### 5. Exemplos de Uso
Um cliente abre um chamado e não responde à pergunta do atendente. Após 1 minuto sem resposta, a extensão envia a mensagem 1. Permanecendo o silêncio, a mensagem 2 é enviada aos 2 minutos e a mensagem 3 aos 4 minutos, finalizando o chamado com sucesso para liberar a fila.

### 6. Suporte
Em caso de dúvidas sobre a configuração da extensão ou réguas de inatividade, entre em contato conosco:

- **E-mail**: contato@wconsulting.tech
- **Telefone/WhatsApp**: 1191628-2384


