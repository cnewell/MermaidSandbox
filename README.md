# MermaidSandbox

## ER diagram with typed fields
```mermaid
erDiagram
	Customer {
		int customerId
		string name
		string address
}
Order {
	int orderId
	double totalPrice
}
Customer ||--o{ Order : places
```
