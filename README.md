# Driven.t - Back-end

## 📝 Sobre

Driven.t é uma solução de gerenciamento de eventos. Você pode gerenciar todos os aspectos do seu evento como o evento em si, localidade, reserva de quartos, dentre outros.

OBS: Este é apenas um segmento do projeto Drivent. Para ter acesso aos outros repositórios
- [Clique aqui para o segmento de implementação Typescript](https://github.com/Reiony/drivent1)
- [Clique aqui para o segmento de implementação de PrismaORM](https://github.com/Reiony/drivent-prisma)
- [Clique aqui para o segmento de implementação de Testes de Integração](https://github.com/Reiony/drivent_tintegracao)

## Tecnologias
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>


## 🧪 Testes

1. Configure o banco de dados PostgreSQL para testes:
2. Configure o arquivo `.env.test`
3. Execute todas as migrações do banco de dados para testes:

```bash
npm run test:migration:run
```

4. Rode os testes:

```bash
npm run test
```


## 💻 Como iniciar a API

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/drivent-4.git
cd drivent-4
```

2. Instale as dependencias

```bash
npm i
```

3. Crie um banco de dados PostgreSQL com o nome que desejar
4. Configure o arquivo `.env.development` 
5. Execute todas as migrações do banco de dados:

```bash
npm run dev:migration:run
```

6. Preencha o banco de dados:

```bash
npm run dev:seed
```

7. Inicie o back-end em ambiente de desenvolvimento:

```bash
npm run dev
```
