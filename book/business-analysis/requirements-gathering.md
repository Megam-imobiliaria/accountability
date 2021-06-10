# Levantamento de requisitos

* A aplicação deve ser acessivel todo o tempo, de qualquer lugar através da web, mantendo persistência de dados indefinidamente

* Deve ser possível gerenciar o cadastro de **Pessoas**: \
    Permissão: Operador \
    Campos:
    - **Nome** - *Texto*
    - **CPF/CNPJ**: *Código*
    - **Tipo**: *[Física, Júridica]*
    - **Contato(s)**
    - Documento(s)
    - **Endereço**


* Deve ser possível gerenciar o cadastro de **Imóvies** \
    Permissão: Operador \
    Campos:
    - **Propietário**: *Pessoa*
    - **Tipo**
    - **Endereço**
    - **Atributo(s)**
    - Documento(s)
    - Custo(s)


* Deve ser possível gerenciar o cadastro de **Contratos** \
    Permissão: Operador \
    - Campos:
    - Situação: *[Negociação, Assinado]*
    - Imóvel
    - Locatátio(s): *Pessoa*
    - Fiador(es): *Pessoa*
    - Imobiliária: *Pessoa*

    - Um **Contrato** estabelece uma relação de responsabilidade (dívida) sob cada custo associado ao **Imóvel** locado

...

## Modelo conceitual

![Modelo Coinceitual](./img/conceptual_model.png)
