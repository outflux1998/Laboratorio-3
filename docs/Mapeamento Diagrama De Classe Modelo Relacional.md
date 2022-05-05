<style> 
    underline{
        text-decoration: underline;
    }
</style>

# Mapeamento Modelo Relacional
NaturalPersonUser(@id, CPF, Wallet, <underline>idUser</underline>)

Student(@id, SSN, Address, CollegeProgram, BankAccount, <underline>idNaturalPersonUser</underline>)

Teacher(@id, department, BankAccount, <underline>idNaturalPersonUser</underline>)

User(@id, Name, Email, Password)

LegalPersonUser(@id, CNPJ, <underline>idUser</underline>, <underline>idInstitution</underline>)

Partner(@id, Name, <underline>idOffer</underline>)

Offer(@id, Name, Cost, <underline>idCoupon</underline>)

Institution(@id, Name, <underline>idStudent</underline>, <underline>idOffer</underline>)

History(@id, Name, <underline>idBankAccount</underline>)

BankAccount(@id, Coins)

[back](../README.md)