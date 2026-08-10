BRZ1 Smart Finance

Controle financeiro pessoal inteligente, organizado e visual.

O BRZ1 Smart Finance é um aplicativo Android desenvolvido para centralizar contas, despesas, cartões, parcelamentos, valores de terceiros, comprovantes e metas de economia em uma experiência simples e moderna.

Este repositório é uma apresentação pública para portfólio. O código-fonte do aplicativo é privado e não está disponível para download.

Sobre o projeto

O aplicativo foi pensado para facilitar a organização financeira do dia a dia. Em um único ambiente, o usuário pode acompanhar suas movimentações, registrar pagamentos, controlar parcelamentos, visualizar análises e gerar relatórios.

As demonstrações e imagens publicadas neste repositório utilizam somente dados fictícios, sem informações pessoais ou financeiras reais.

Principais recursos

Dashboard financeiro com visão mensal.

Cadastro e acompanhamento de despesas pessoais.

Controle de contas fixas com checklist de pagamento.

Gestão de cartões, compras e parcelamentos.

Divisão de despesas e controle de valores de terceiros.

Organização de comprovantes e anexos.

Desafio de economia com projeções semanais e mensais.

Análise de gastos por categorias.

Indicadores e orientações para melhorar a organização financeira.

Geração de relatórios em PDF e imagens para compartilhamento.

Backup de dados em JSON.

Autenticação e sincronização de informações pela nuvem.

Funcionamento dos parcelamentos

Ao cadastrar uma compra parcelada, o aplicativo cria as parcelas mensais e mantém todas vinculadas por um identificador de grupo. Isso permite gerenciar uma parcela individualmente ou excluir todo o parcelamento de forma organizada.

Arquitetura

O projeto utiliza a arquitetura MVVM (Model–View–ViewModel):

View: telas construídas com Jetpack Compose e atualizadas de acordo com o estado da aplicação.

ViewModel: centraliza as regras financeiras, cálculos e comunicação com o banco de dados.

Model: representa contas, cartões, despesas, pagamentos, terceiros e desafios.

Tecnologias utilizadas

Kotlin

Android Studio

Jetpack Compose

Material Design 3

MVVM

Firebase Authentication

Cloud Firestore

Coil Compose

FileProvider

Armazenamento privado do Android

Privacidade e segurança

Os dados são organizados por usuário autenticado. Comprovantes locais são armazenados na área privada do aplicativo no dispositivo.

Por segurança, este repositório não contém:

código-fonte do aplicativo;

arquivo google-services.json;

chaves, senhas ou credenciais;

dados financeiros reais;

identificadores de usuários;

comprovantes pessoais;

configurações privadas do Firebase.

Em uma implantação comercial, regras de acesso, autenticação, armazenamento e tratamento de dados devem ser configuradas de acordo com as necessidades do cliente e com a LGPD.

Demonstração

O vídeo apresenta o fluxo real do aplicativo em um smartphone Android, utilizando somente dados fictícios. A demonstração inclui configuração inicial, cadastro de cartões, lançamentos, parcelamentos, checklist de contas, relatórios e ajustes.

▶️ Assistir à demonstração do BRZ1 Smart Finance

Duração: 1 minuto e 44 segundos.

Durante a apresentação também são destacadas as principais tecnologias utilizadas no projeto: Kotlin, Jetpack Compose, Material Design 3, MVVM, Firebase Authentication, Cloud Firestore, geração de PDF e backup JSON.

Próximas melhorias

Notificações de vencimento.

Proteção por biometria.

Sincronização de comprovantes na nuvem.

Novos gráficos e indicadores financeiros.

Ampliação das opções de relatórios.

Melhorias visuais e de acessibilidade.

Disponibilidade

O BRZ1 Smart Finance é um projeto privado em desenvolvimento e evolução. Este repositório tem finalidade exclusivamente demonstrativa e apresenta os conceitos, recursos e tecnologias utilizados.

O conteúdo aqui publicado não concede autorização para copiar, redistribuir, comercializar ou reproduzir o aplicativo.

Autoria

Desenvolvido por beto-dev94Marca BRZ1

© 2026 BRZ1. Todos os direitos reservados.
