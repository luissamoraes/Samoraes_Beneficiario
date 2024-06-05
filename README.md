Samoraes_Beneficiario
Projeto em Java Spring boot versão 17 para Empresa EKan.

Projeto desenvolvido para a avalicao da Ekan que consiste na criacao de uma aplicação utilizando Java e Spring Boot que forneça uma API REST para manter o cadastro de beneficiários de um plano de saúde.

Aprendizados
Gostaria de manifestar minha profunda gratidão pela oportunidade inestimável de participar deste projeto de avaliação. Foi uma vivência enriquecedora que acrescentou de maneira significativa ao meu desenvolvimento profissional. Durante este período de avaliação, pude me envolver em um desafio que ampliou minha compreensão e habilidades em diversas áreas. Cada obstáculo foi uma chance de aprendizado, e sou grato pela oportunidade de enfrentá-los. A colaboração neste projeto criou um ambiente favorável ao meu crescimento, e os conhecimentos adquiridos certamente terão um impacto positivo na minha trajetória profissional. Agradeço pela confiança depositada em mim e por me permitir participar ativamente desta experiência singular.

Estou ansioso para continuar contribuindo e aplicando os ensinamentos adquiridos ao longo desta jornada.

Atenciosamente, Luis Samoraes

## Funcionalidades

- Cadastro de beneficiario e Documento ❌ 
- Listagem de todos os beneficiarios ✅
- Listagem de todos os documentos relacionados ao beneficiario ✅
- Atualizacao no perfil do beneficiario ✅
- Remocao do perfil do beneficiario ✅


## Uso/Exemplos

##Post

```json
{
    "nome" : "Luis Augusto de Sa de Moraes",
    "telefone" : "32 984238262",
    "dataNascimento" : "03/07/1977",
    "documentos" : [
        {
            "tipoDocumento" : "CPF",
            "descricao" : "Cadastro de pessoa fisica"
        },
        {
            "tipoDocumento" : "RG",
            "descricao" : "Registro geral"
        }

    ]
}
```


## Stack utilizada

**Java, Spring Boot , H2 e Swagger**

## Rodando localmente

Clone o projeto

```bash
  git clone https://github.com/luissamoraes/Samoraes_Beneficiario.git

Fazendo o update das dependecias do maven
```bash
 mvn clean install
```

Rodar a main na IDE de sua preferencia


## Autor

- [@luissamoraes](https://github.com/luissamoraes)

