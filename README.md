# Bank System Project

## Overview
This project aims to create a simple banking system to understand object associations in Object-Oriented Programming (OOP). The system includes entities like accounts, bank cards, people, transactions, and products. Various types of nested classes are used to implement these entities.

## Objectives
- Develop skills in object associations in OOP.
- Use Static Nested Classes, Nested Inner Classes, and Anonymous Inner Classes appropriately.

## Requirements

### 1. Account Entity
- An account has a money balance.
- An account supports three currencies but operates with one currency at a time.

### 2. Bank Card Entity
- The balance of an account can only be withdrawn or topped up through a bank card.

### 3. Person Entity
- A person can log in to the system.
- Some people have an account, while others may not.
- All have bank cards.
- Not all have accounts because the account owner can issue bank cards to their relatives.

### 4. Transaction History
- Create a transaction history object to monitor all transactions at the beginning of the program.
- Display the list of transactions at the end of the program. (This task is optional as it is challenging.)

### 5. Card Issuance
- A bank card is issued from an account.
- Both the card and the account have an owner—a person.

### 6. Product Entity
- Define product fields, including a price field.

### 7. Initial Data Generation
- Create several people, accounts (with balances), and bank cards at the start of the program.
- Generate a list of 10 products.

### 8. User Login and Information Display
- After login, a person sees all their information, card details, and account information.
- Show if the person is the account owner or just an authorized user.

### 9. Product Purchase
- Display the list of products and ask the user which product and quantity they want to buy.
- Users can purchase products multiple times.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
