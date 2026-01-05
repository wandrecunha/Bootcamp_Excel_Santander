Controle de Imposto de Renda

Este projeto foi desenvolvido como parte de um desafio prático na DIO. 

O objetivo é criar uma ferramenta robusta e amigável no Microsoft Excel para organizar informações essenciais para a declaração anual de Imposto de Renda (IRPF).

A planilha foca na experiência do usuário (UX), utilizando validações de dados, formatações personalizadas e navegação intuitiva entre telas.

Funcionalidades e Telas
O projeto é dividido em três módulos principais de entrada de dados:

---

1. Dados do Titular (Identificação)
Nesta tela, o usuário preenche suas informações básicas com máscaras de entrada automáticas.

Campos: Nome, CPF, Nascimento, Título de Eleitor, Cônjuge, Endereço, Contatos e Perguntas de Controle.

Destaques Técnicos:

Formatação Personalizada: Máscaras automáticas para CPF (000"."000"."000"-"00), Telefone e Celular.

Validação de Dados: Menus suspensos (Sim/Não) para alterações cadastrais e residentes no exterior.

UX: Alinhamento estratégico de rótulos e campos para facilitar a leitura.

---

2. Informes de Rendimentos Bancários
Espaço dedicado para consolidar saldos e instituições financeiras.

Destaques Técnicos:

Tabelas Auxiliares: Uso de listas dinâmicas para seleção de Bancos.

Mensagens de Erro: Alertas personalizados para garantir que apenas bancos da lista sejam selecionados.

Cálculos Automáticos: Soma total de valores formatada em Moeda ($).

---

3. Notas de Entrada (Receita)
Registro detalhado de entradas mensais para controle de fluxo de caixa.

Destaques Técnicos:

Formatação de Data: Uso do formato personalizado MMMM-AA (ex: Janeiro-26).

Categorização: Validação para tipos de entrada (Holerite, Freelancer, CNPJ), Honorários.

Atalhos: Implementação do uso de CTRL + ; para agilizar a inserção de datas.

---

Diferenciais do Projeto
Navegação Dinâmica: Criação de botões "Próximo" e "Anterior" utilizando formas e hiperlinks para transição entre abas.

Painel de Seleção: Organização de objetos e formas para um layout limpo.

Segurança e Proteção: Bloqueio de células com fórmulas.

Liberação apenas de campos editáveis para o usuário final.

Proteção da estrutura da planilha para evitar alterações acidentais.

Conhecimentos Aplicados
Formatação Condicional e Personalizada.

Validação de Dados (Listas suspensas e mensagens de entrada/erro).

Fórmulas Matemáticas (SOMA).

Design de Interface (UI) no Excel (Uso de bordas, alinhamentos e painel de seleção).

Segurança de Dados (Proteção de planilhas e bloqueio de células).

---

Desenvolvido por Wandré Cunha.
