## React 리스트 렌더링 map + key
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

### 숫자 ex) 1,000,000 으로 변환하려면 toLocaleString()

zustand - 전역 상태 관리 라이브러리
zustand-middleware localstorage 처리 관련 라이브러리
vue에선 vuex 사용

ide - vs code, kiro(아직 안됨), cursor, windsurf
