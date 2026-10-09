# Clínica Nufit — Projeto de LAN

Projeto de rede local de uma clínica fictícia de nutrição, desenvolvido no Cisco Packet Tracer.

## Identificação

- **Instituição:** Faculdade Serra Dourada
- **Curso:** Análise e Desenvolvimento de Sistemas
- **Turma:** 1º período
- **Disciplina:** Redes de Computadores
- **Professor:** Guibson Krause
- **Integrantes:** Thais Couto Henchen e Felipe Kuhn

## Sobre o projeto

A Clínica Nufit possui recepção, três consultórios e setor administrativo/financeiro, distribuídos em um único andar.

A rede utiliza topologia em estrela estendida, com cinco computadores, um notebook, duas impressoras, quatro câmeras, quatro switches e um roteador sem fio. Um celular representa o acesso de um paciente à rede de convidados.

A planta ilustrativa da clínica está no relatório em PDF. 

## Como abrir

1. Baixe o arquivo `clinica-nufit-final.pkt` deste repositório. No GitHub, abra o arquivo e use a opção **Download raw file**.
2. Abra o Cisco Packet Tracer.
3. Selecione **File → Open / Arquivo → Abrir** e escolha o arquivo baixado.

O projeto foi desenvolvido no Cisco Packet Tracer **9.0.1.0858**. Recomenda-se utilizar essa versão para reproduzir a demonstração.

## Configuração e testes

A rede interna utiliza endereços IPv4 privados da rede `192.168.1.0/24`. O endereço LAN do roteador é `192.168.1.1`.

Foram realizados testes de ping do notebook para os cinco computadores, as duas impressoras e as quatro câmeras, com respostas sem perda de pacotes.

A rede de convidados `Nufit-Pacientes` utiliza WPA2-Personal com AES e endereçamento por DHCP. O bloqueio de acesso à recepção, ao financeiro e à impressora da recepção foi verificado, enquanto o notebook da equipe manteve acesso a esses recursos.

## Limites da simulação

O projeto demonstra conectividade local e restrições de acesso. Não inclui conexão com a internet real, simulação de serviços externos, impressão efetiva de documentos ou gravação de vídeo.

As senhas configuradas são exclusivas deste projeto acadêmico.

