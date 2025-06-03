# Crime Detection in Credit Card Fraud

## Project Overview

This Java-based project aims to develop a **credit card fraud detection system** that efficiently flags suspicious transactions in real time using a rule-based approach. It enhances security by evaluating transaction details such as amount and location, ensuring legitimate transactions are processed while potential frauds are flagged for review.

## Technologies Used

- Java AWT (GUI)
- Java Standard Library
- Java Collections (`ArrayList`, `List`)

## Project Structure

```
CreditCardFraud/
├── CreditCardFraud.java      # Main application file
├── README.md                 # Project documentation
└── screenshots/              # Screenshots of application output
```

## Modules

### 1. Transaction Module
- Represents a single credit card transaction.
- Attributes:
  - `transactionId`
  - `creditCardNumber`
  - `amount`
  - `location`
  - `timestamp`

### 2. Fraud Detection System
- Contains logic to detect:
  - Amounts over `$5000`
  - Transactions from high-risk locations
- Flags suspicious transactions using simple conditional checks.

### 3. Main Application (AWT GUI)
- Takes user input for:
  - Card number
  - Amount
  - Merchant/location
- Displays result as either:
  - `Transaction is normal`
  - `Fraud Detected: Amount exceeds $10,000!`

## How to Run

1. Compile the Java file:

   ```bash
   javac CreditCardFraud.java
   ```

2. Run the program:

   ```bash
   java CreditCardFraud
   ```

3. Enter the required transaction details in the GUI and click **"Check Fraud"**.

## Future Improvements

- Integrate machine learning algorithms for dynamic fraud pattern detection.
- Add support for real-time transaction streaming (e.g., using Apache Kafka).
- Connect to a backend database for storing flagged transactions.
- Implement SMS/email alerts for flagged activities.

## References

1. Bolton, R. J., & Hand, D. J. (2002). *Statistical Fraud Detection: A Review*. Statistical Science.
2. Bhattacharyya, S., et al. (2011). *Data Mining for Credit Card Fraud Detection: A Comparative Study*.
3. [Apache Kafka](https://kafka.apache.org/)
4. [Mastercard AI Fraud Detection](https://www.mastercard.com/)

## Author

**Padmapriya S**  
Department of Artificial Intelligence and Data Science  
K. Ramakrishnan College of Technology  
FOR ANY QUERY CONTACT : padmapriyasaravanan28@gmail.com
