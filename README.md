# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab "Criando máquinas Virtuais na Azure" na DIO

# Resumo do "Lab" - Criação de Máquina Virtual no Azure

Durante o desenvolvimento do "Lab" proposto no vídeo, mesmo sem a criação prática de uma máquina virtual (MV), aprendi diversos pontos importantes sobre o processo de criação e as configurações envolvidas. Seguem as lições que eu aprendi com essa atividade:

- Compreendi o que é o SLA (Service Level Agreement) e as diferentes opções oferecidas conforme o tempo de inatividade, variando de 99% até 99,999%.
- Naveguei até o menu "Todos os Serviços" no portal do Azure, onde é possível iniciar a criação de uma MV.
- Observei as "Opções de disponibilidade", e como tenho a opção de selecionar até 3 zonas diferentes para distribuir as MVs.
- Descobri que o ícone "i" oferece informações importantes sobre as instâncias e, em alguns casos, dentro do “i” há links com "Saiba mais" que direcionam para o Docs do MS Learn — uma fonte recomendada pela instrutora Valéria Baptista para aprofundamento.
- Aprendi que ao selecionar múltiplas zonas, o sistema recomenda a criação de uma **VMSS** (Virtual Machine Scale Set vi no Doc), embora não tenha sido explicado em detalhes o que seja, como funciona e quando optar por ela.
- Notei que cada decisão tomada na configuração da MV impacta diretamente no nível de SLA oferecido.
- Entendi que, ao criar uma MV, também preciso criar uma Conta de Armazenamento.
- Dentro da criação da conta de armazenamento, aprendi sobre as opções de replicação dos dados: LRS, GRS, ZRS e GZRS.
- Compreendi que a escolha da estratégia de replicação impacta diretamente no SLA, na alta disponibilidade e nos custos da solução.
- A Valéria Baptista reforçou a importância de alinhar essas escolhas com as necessidades e expectativas da empresa para quem estivermos oferecendo o serviço, evitando futuras insatisfações.

> _Mesmo sem executar o Lab na prática, o conteúdo foi essencial para compreender os conceitos iniciais relacionados à criação de máquinas virtuais no Azure._

