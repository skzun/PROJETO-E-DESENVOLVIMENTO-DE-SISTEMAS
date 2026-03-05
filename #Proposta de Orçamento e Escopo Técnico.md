# Proposta de Orçamento e Escopo Técnico

## 1. Dados do Cliente

- **Nome/Razão Social:** Nordeste Manutenção
- **CPF/CNPJ:** Aguardando Envio
- **Endereço:** Rua Vila São Francisco 344
- **Telefone:** 74 99088562

## 2. Resumo do Projeto

Desenvolvimento de um **Sistema de Gestão Desktop** para controle de locadora de veículos. O sistema visa substituir o controle manual (Caderno/WhatsApp) por uma solução automatizada que gerencia a frota, calcula multas complexas e bloqueia veículos em manutenção.

## 3. Arquitetura Técnica

O projeto será desenvolvido utilizando tecnologias robustas de mercado, garantindo segurança e integridade dos dados:

- **Linguagem:** Java (Versão 17 LTS).
- **Interface Gráfica (View):** Java Swing desenvolvida no IDE **Apache NetBeans**.
- **Persistência de Dados (Model):** Framework **Hibernate (JPA)** para mapeamento Objeto-Relacional, eliminando SQL manual e prevenindo falhas de segurança.
- **Banco de Dados:** **MySQL Server 8.0**.
- **Relatórios:** Biblioteca **JasperReports** para geração de contratos em PDF.

## 4. Funcionalidades do Escopo (MVP)

1. **Gestão de Frota:** Cadastro de veículos com categorização (Hatch, Sedan, Van) e controle de status (**Disponível, Alugado, Em Manutenção**).
2. **Motor de Locação:** Fluxo de "Balcão" para locação imediata (sem reservas futuras).
3. **Financeiro Automatizado:**
    - Cálculo de diárias baseado na categoria do carro.
    - Cálculo automático de multas por atraso (Regra de tolerância de 6h e 12h).
4. **Emissão de Documentos:** Geração automática do Contrato de Locação em PDF para assinatura.

## 6. Estimativa de Investimento
|  Fase  |          Descrição                       | Horas Estimadas   | Valor  |
|   1    | Levantamento de Requisitos e Design      | 20h               | Gratis |
|   2    | Desenvolvimento Back-end (Java/Hibernate)| 40h               | Gratis |
|   3    | Desenvolvimento Front-end (Swing)        | 30h               | Gratis |
|   4    | Testes e Implantação                     | 10h               | Gratis |
| **TOTAL** | **Sistema Completo (Código Fonte + Instalação)** |**100h**| Gratis |

---