# Debit & Credit 5.3.3
This update has three small features that I believe are worth sharing with you.

### Improvements to Reports

When you run the “What do I spend my money on?” report, you get all of your expenses nicely grouped together. But what happens when you spent some money on a particular category but then were refunded? 

Previously the app would exclude a category like that from this report.  Now the app will include them with the zero amount. That is a more correct approach that allows you to see a complete picture of your expenses.

### Option To Convert Transaction Descriptions Into Notes

When you create a new transaction, you can provide a description and/or a note for it. What is the difference between the two?

Well, a description is supposed to be reusable. Something that you can enter once and then select again from the list of descriptions. For example, if you just had a check-up with your dentist, you can use “Dentist” as a description for your transaction and “Health” as a category. Certainly, that won’t be your last visit to a dentist so you will be able to reuse that description.

Notes, on the other hand, are designed to be unique. You can put a reference number or a check number. Whatever information you want.

Every time you open the app settings to manage your metadata, the app checks your descriptions and if it finds too many one-time used descriptions, it will suggest converting them into notes. That is useful not only for the purpose of visual consistency (it can be hard to select from a long list of descriptions) but since that will improve your iCloud syncing performance (when reinstalling the app and performing a complete sync).

### Improved Search Operators

[Search operators](https://debitandcredit.app/help/) is a powerful feature in the app. With its help, you can easily make a search query to find a particular subset of transactions. For instance, you can find transactions that both have a category “Groceries” and payee “Walmart” by entering category:”Groceries” payee:”Walmart” into the search field.

But what if you want to find transactions that have no category or payee? Now you can do that by entering category:none. Similarly, you can type “none” for a description, payee, tag or notes.