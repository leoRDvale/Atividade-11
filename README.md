# Atividade-11

Considere as Entidades Aluno, Professor, Funcionário e Departamento com seus respectivos atributos. Implemente uma API com essas entidades.

Aluno

id_aluno (UUID ou inteiro)

nome_completo

data_nascimento

cpf/matricula_nacional (ou documento equivalente)

matricula (código interno/RA)

email_institucional

telefone

----------------

Professor

id_professor (UUID ou inteiro)

nome_completo

cpf/registro_funcional

email_institucional

telefone

titulacao (Mestre, Doutor, Pós-Doc, etc.)

area_de_atuacao (palavras‑chave)

regime_trabalho (20h, 40h, DE)

----------------

Funcionário

id_funcionario (UUID ou inteiro)

nome_completo

cpf/registro_funcional

email_institucional

telefone

cargo (ex.: técnico administrativo, assistente, analista)

tipo_vinculo (CLT, estatutário, terceirizado, bolsista)

----------------

Departamento

id_departamento (UUID ou inteiro)

nome

sigla

centro/unidade_academica (se aplicável)

chefe_departamento_id (FK para Professor ou Funcionário)

email_contato

telefone/ramal

localizacao (prédio/sala)
