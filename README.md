Azure Service Bus Demo 🎯
🚀 This project demonstrates how to implement Azure Service Bus in a .NET application using Topics & Subscriptions for asynchronous messaging.

📌 Features
✅ Publish messages to Azure Service Bus Topic
✅ Consume messages from multiple Subscriptions
✅ Asynchronous messaging using .NET
✅ Utilizes Azure.Messaging.ServiceBus SDK

🔧 Prerequisites
An Azure account
.NET 6 or later
Configured Azure Service Bus (Namespace, Topic, and Subscriptions)
🚀 How to Run the Project
Update the ConnectionString in appsettings.json with your Azure Service Bus credentials.
Run the Producer (Publisher):
sh
Copy
Edit
cd ServiceBus.Producer  
dotnet run  
Run the Consumer (Subscriber):
sh
Copy
Edit
cd ServiceBus.Consumer  
dotnet run  
The consumer should start receiving messages published to the Service Bus Topic 🎉
🛠 Technologies Used
.NET 6
Azure Service Bus
C# Asynchronous Messaging
GitHub Actions (for future CI/CD integration)
🤝 Contributions
Feel free to open an Issue or submit a Pull Request to improve this project! 🚀

