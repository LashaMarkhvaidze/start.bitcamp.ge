# ცვლადები

ჯავასკრიპტში ახალი ცვლადების შექმნა შეიძლება `let`, `const`, და `var`, ქივორდებით.

`let` საშუალებას გვაძლევს შევქმნათ ბლოკის დონის ცვლადი, ანუ მოცემული ცვლადი მხოლოდ იმ ბლოკშია ვალიდური სადაც შეიქმნა.

```text
// myLetVariable აქ არ არის ხელმისაწვდომი

for (let myLetvariable=0; myLetVariable<10; myLetVariable++){
// myLetVariable ხელმისაწვდომია
}

// myLetVariable არც აქ არის ხელმისაწვდომი
```

`const` ქივორდით ხდება ისეთო ცვლადების შექმნა, რომლებიც არ უნდა შეიცვალოს:

```text
const Pi = 3.14 
Pi = 1; // ეს შეცდომას გამოიწვევს, იქიდან გამომდინარე რომ Pi const ქივორდით შეიქმნა, ანუ მისი შეცვლა შეუძლებელია.
```

`var` ქივორდს არ გააჩნია რაიმე სახის შეზღუდვა და მხოლოდ ის იძლევა თავისუფალი, სტანდარტული ცვლადების შექმნის საშუალებას. ასე შექმნილი ცვლადი ფუნქციის დონეზეა ხელმისაწვდომი:

```text
// myVarVariable ხელმისაწვდომია

for (var myVarVariable = 0; myVarVariable < 5; myVarVariable++){
  // აქაც
  }
// და აქაც.
```

როგორც წინა ნაწილში ვახსენე, ცვლადს რომელსაც არ აქვს მინიჭებული რაიმე მნიშვნელობა არის `undefined`.

