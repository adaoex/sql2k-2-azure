# [Projeto]:recycle: Migrando do :older_woman:SQL2K ao :cloud:Azure

## :rocket: Resumo do Projeto 
Nesse projeto pretendo demonstrar a evolução de uma base de dados no  Microsoft SQL Server da versão 2000 até o Microsoft Azure, passando por versões intermediárias no processo.

## 🎯Objetivo do Projeto
Partindo de uma demanda real, mas aqui adaptado pra fins didáticos, pretendo demonstrar o processo de migração de um banco de dados (legado) no Microsoft SQL Server 2000 para a versão mais recente do SGDB e para Cloud (Microsot Azure).

Este projeto de estudo o seguinte escopo macro: 
- :black_square_button:Temos um banco de dados no SQL Server 2000 (Lab Local com Hyper-V)
- :black_square_button:Atender a questão 01: até que versão do SQL Server posso evoluir, com pouco impacto nas aplicações? 
    - Migração: *inplace* ou *side-by-side*
- :black_square_button:Deseja-se estimar o impacto das possíveis alterações nas aplicações 
- :black_square_button:Decisão nº 1: migrar inicialmente para o SQL 2005 ou SQL 2008 R2?


## 👩🏾‍💻Lab (Hyper-V)

* Criar uma interface de rede comum (vswitch_interno)

* :red_circle:Instalação do Microsoft SQL Server 2000: 
    * [Microsoft Windows Server 2003 R2 Enterprise Edition VHD](https://www.microsoft.com/en-us/download/details.aspx?id=19727)
        -  Uma "dica" para criar suas VMs no Hyper-V
    * Microsoft SQL Server 2000 Standard Edition 
