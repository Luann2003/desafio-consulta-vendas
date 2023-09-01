# desafio-consulta-vendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Luann2003/desafio-consulta-vendas/blob/main/LICENSE) 

## Sobre o projeto
Esse projeto Trata-se de um sistema de vendas (Sale) e vendedores (Seller). Cada venda está para um vendedor, e um
vendedor pode ter várias vendas.

Este projeto foi desenvolvido como parte dos meus estudos no programa Dev Superior, um programa intensivo de desenvolvimento back-end.

**Principais Funcionalidades**:
## 1. Consulta de Vendas

- [IN] O usuário pode informar opcionalmente:
  - Data inicial.
  - Data final.
  - Um trecho do nome do vendedor.

- [OUT] O sistema fornece uma listagem paginada contendo:
  - ID da venda.
  - Data da venda.
  - Quantia vendida.
  - Nome do vendedor.

### Informações Complementares

- Se a data final não for informada, o sistema considerará a data atual do sistema.

- ![](https://github.com/Luann2003/desafio-consulta-vendas/blob/main/date%20and%20name.png)

## 2. Sumário de Vendas por Vendedor

- [IN] O usuário pode informar opcionalmente:
  - Data inicial.
  - Data final.

- [OUT] O sistema fornece uma listagem contendo:
  - Nome do vendedor.
  - Soma de vendas deste vendedor no período informado.

### Informações Complementares

- Se a data final não for informada, o sistema considerará a data atual do sistema.
- ![](https://github.com/Luann2003/desafio-consulta-vendas/blob/main/users.png)

```bash
# Clone o repositório
git clone https://github.com/Luann2003/desafio-consulta-vendas.git

# Navegue até o diretório do projeto
cd desafio-consulta-vendas

# Compile e execute o programa
java main.java
```

## Conclusão

Este projeto representou uma oportunidade valiosa para expandir meus conhecimentos e habilidades em desenvolvimento. Durante sua realização, me aprofundei nas complexidades das consultas JPA e JPQL, bem como na integração eficaz da JPA no ambiente Spring Boot Java para consultas de dados.

Ao longo deste projeto, não apena consegui construir um sistema eficiente de consulta e resumo de vendas, mas também aprimorei minhas habilidades técnicas. 

# Autor
Luan Victor de Ramos Luciano

https://www.linkedin.com/in/luan-luciano-1603b4197/

