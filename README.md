# Davi Soares :sunglasses:
```csharp
Developer davi = Developer
    .Married()
    .BornIn(Countries.Brazil, year: 1997)
    .CodesIn(language => language
        .JavaScript()
        .HTML()
        .CSS()
        .React())
    .Interested(@in => @in
        .SoftwareArchitecture()
        .DomainDrivenDesign()
        .DistributedSystems()
        .LinkedIn("https://www.linkedin.com/in/davi-soares-a7ba79221/"));

while (davi.HasLife)
{
    davi.Travel();
    davi.EnjoyLife();
    davi.Code();
}

// todo: find out what is next 😅
```
