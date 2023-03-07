import Bank_Account
class User:
    def __init__(self, name, email):
        self.name = name
        self.email = email
        self.account = Bank_Account(int_rate=0.02, balance=0)
        self.display_user_balance = Bank_Account.Captain_Rex.balance
    
    # other methods
    
    def make_deposit(self, amount):
        self.account += amount
        return self

    def make_withdrawl(self, amount):
        self.account -= amount

    def display_user_balance(self, balance):
        print(Bank_Account.Captain_Rex.balance)
        print(Bank_Account.General_Skywalker.balance)

        for BankAccount in Bank_Account:
            pass
