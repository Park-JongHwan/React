
```javascript

const accounts: Account[] = [
  { id: '1001', name: '급여통장', balance: 3000000 },
  { id: '1002', name: '비상금통장', balance: 500000 },
];

return (
  <div>
    {accounts.map((acc) => (
      <AccountItem key={acc.id} {...acc} />
    ))}
  </div>
);
```

{...acc} -> 펼침연산자
