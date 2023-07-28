---
title: "Operators"
---

# Operators

როცა RxJS-ის დახმარებით რაიმე ამოცანის ამოხსნა გვჭირდება, ხშირ შემთხვევაში
ამისთვის უკვე არსებობს ოპერატორი. RxJS-ს გააჩნია ოპერატორების ძალზედ დიდი
არსენალი, რაც ერთი შეხედვით ძალიან დამთრგუნველია, თუმცა ნუ შეგეშინდებათ.
არის ოპერატორების რაღაც ძირითადი ნაწილი, რომელიც ყველაზე ხშირად დაგვჭირდება
და თუ ჩვენ შემდგო მრაიმე კონკრეტული ახალი ოპერატორის შერჩევა დაგვჭირდება,
შეგვიძლია მოვიშველიოთ
[ოპერატორების ასარჩევი კითხვარი](https://rxjs.dev/operator-decision-tree)
რომელიც დაგვეხმარება სწორი ოპერატორის შერჩევაში.

არსებობს ოპერატორების ორი ზოგადი კატეგორია:

- [შექმნის ოპერატორები (creation operators)](./creation-operators.html) - სტრიმების
  შესაქმნელად;
- [ფაიფის ოპერატორები (pipeable operators)](./pipeable-operators.html) - არსებულ სტრიმზე ოპერაციების ჩასატარებლად.