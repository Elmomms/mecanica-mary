# AutoFix com Docker

Com o Docker instalado, abra o terminal nesta pasta e execute:

```bash
docker compose up --build
```

Depois abra no navegador:

http://localhost:8080

Login de teste:

- E-mail: maryana@gmail.com
- Senha: 123456

Para parar:

```bash
docker compose down
```

Para apagar também os dados do banco:

```bash
docker compose down -v
```

O Docker cria automaticamente o MySQL, o banco `autofix`, o backend Node/Express e o frontend.
O Prisma cria as tabelas e o seed cadastra os dados de teste.
