# Sistema de Reserva de Hotel - Desafio DIO WEX

Projeto em C# desenvolvido como parte do Bootcamp WEX na [DIO](https://www.dio.me/).  
O objetivo é simular um sistema de reserva de hotel com cadastro de hóspedes, suíte e cálculo do valor total da hospedagem.

## 📌 Funcionalidades
- Cadastro de suíte (tipo, capacidade, valor da diária)
- Cadastro de reserva (quantidade de dias e hóspedes)
- Validação antecipada de capacidade de hóspedes
- Validação de nomes não vazios e sem duplicidade
- Cálculo do valor total com desconto de 10% para reservas acima de 10 dias
- Tratamento de erros e mensagens amigáveis

## 🛠 Tecnologias
- .NET 9.0
- C#

## 🚀 Como executar
1. Clone este repositório:
   ```
   git clone https://github.com/<seu-usuario>/sistema-reserva-hotel-wex-dio.git

2. Acesse a pasta do projeto:
```
cd sistema-reserva-hotel-wex-dio/HotelWex
```

3. Execute o projeto:
```
dotnet run
```

📷 Exemplo de uso

=== Desafio Sistema de Hospedagem ===

```
Tipo da suíte: Luxo
Capacidade da suíte (número): 2
Valor da diária (ex.: 199,90): 250
Dias reservados: 12
Quantos hóspedes deseja adicionar? 2
Nome do hóspede 1: Ana
Nome do hóspede 2: João

Quantidade de hóspedes: 2
Valor total da reserva: R$ 2.700,00
```

Desenvolvido no Bootcamp WEX pela DIO 🚀

---

## 📦 Comandos para subir no GitHub
No terminal, dentro da pasta **raiz do repositório** (`D:\github\sistema-reserva-hotel-wex-dio`):

```powershell
git init
git add .
git commit -m "Desafio Sistema de Reserva de Hotel - DIO WEX"
git branch -M main
git remote add origin https://github.com/<seu-usuario>/sistema-reserva-hotel-wex-dio.git
git push -u origin main
