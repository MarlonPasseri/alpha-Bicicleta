# Sistema de Aluguel de Bicicletas 🚴‍♂️

Este é um sistema simples de aluguel de bicicletas desenvolvido em Java utilizando a biblioteca **Swing** para a interface gráfica. O objetivo principal do projeto é gerenciar o aluguel de bicicletas, incluindo funcionalidades de administração e controle de usuários.

---

## Funcionalidades 🛠️

### Para o Administrador
- Login como administrador.
- Cadastro de novos usuários.
- Adição de novas bicicletas ao sistema.
- Alteração de informações de usuários e bicicletas.
- Visualização de registros de aluguel.

### Para os Usuários
- Login no sistema.
- Aluguel de bicicletas disponíveis.
- Devolução de bicicletas alugadas.

---

## Estrutura do Projeto 📂

O projeto está dividido nas seguintes classes principais:

### **BikeRentalSystem**
- Classe principal que inicializa o sistema e gerencia a interface gráfica.
- Contém o menu principal e as abas para administração e usuários.

### **User**
- Representa um usuário do sistema, contendo os atributos:
  - `username` (nome de usuário)
  - `password` (senha)

### **Bike**
- Representa uma bicicleta no sistema, contendo os atributos:
  - `id` (identificador único da bicicleta)
  - `name` (nome da bicicleta)

### **RentalRecord**
- Representa um registro de aluguel, contendo os atributos:
  - `bikeId` (ID da bicicleta alugada)
  - `rentalTime` (tempo de aluguel em milissegundos)

---

## Pré-requisitos ⚙️

Certifique-se de ter os seguintes requisitos instalados no seu sistema:

- **Java Development Kit (JDK)** 8 ou superior.
- Um ambiente de desenvolvimento Java, como IntelliJ IDEA ou Eclipse.

---

## Como Executar 🚀

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-aluguel-bicicletas.git
