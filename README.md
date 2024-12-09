# Dente Convênio 

**Dente Convênio** é um projeto desenvolvido para estudo e prática de conceitos sobre microserviços. Ele simula um sistema de convênio odontológico, oferecendo funcionalidades para diferentes perfis de usuários, como consultórios, beneficiários, dentistas e empresas.

---

## 🎯 Objetivo

Explorar a arquitetura baseada em microserviços com tecnologias modernas, promovendo a prática de conceitos como comunicação assíncrona, escalabilidade e segurança. 

---

## ✨ Principais Recursos

- **Registro de Usuários**:
  - Consultório: Define horários de atendimento e benefícios que o consultório cobre.
  - Empresa: Gerencia colaboradores (beneficiários) e assina planos que geram descontos aos colaboradores.
  - Beneficiário: Assina planos com diversos benefícios.
  - Dentista: É designado a consultas agendadas.

- **Gestão de Planos**:
  - Empresas podem associar colaboradores como beneficiários e assinar planos para obter descontos.
  - Beneficiários podem escolher entre planos disponíveis.

- **Gestão de Consultas**:
  - Consultórios podem agendar e gerenciar consultas.
  - Dentistas são designados automaticamente a consultas disponíveis.

---

## 🛠️ Tecnologias Utilizadas

- **Backend**: Spring Boot, Spring JPA, Spring Security, Spring Scheduled, Spring Web
- **Banco de Dados**: MySQL
- **Mensageria**: RabbitMQ
- **Cache**: Redis
- **Containerização**: Docker
- **Gerenciamento de Dependências**: Maven

---

## 🚀 Como Rodar o Projeto

### Pré-requisitos
- **Docker**: Necessário para rodar os serviços.

### Passos
1. Clone este repositório:

```bash
git clone https://github.com/Tessaro03/denteconvenio.git
cd denteconvenio
```

2. Execute o docker-compose:

```bash
docker-compose up
```

Acesse os serviços pelos endpoints configurados (consulte a documentação detalhada para endpoints e portas).

## 📖 Documentação

Para mais informações sobre a API, configuração e detalhes técnicos, acesse a [documentação oficial](https://docs.google.com/document/d/14e_HUlZQA9xIeQr-wkTrSroL5twIMZdMHr2xs4kJ_Ng/edit?usp=sharing).

## 🧑‍💻 Autor

Desenvolvido por [Tessaro03](https://github.com/Tessaro03).
