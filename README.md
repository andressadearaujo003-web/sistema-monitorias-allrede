# Sistema de Monitorias - Retenção Allrede Telecom

Este pacote contém o projeto React (+ Tailwind) pronto para deploy.

## Passos rápidos

1. Instale dependências:

```
npm install
```

2. Atualize `src/firebase.js` com as credenciais do seu projeto Firebase.

3. Para desenvolvimento:

```
npm run dev
```

4. Build e deploy (Vercel recomendado):

- Faça push para um repositório GitHub.
- Conecte o repositório ao Vercel e faça deploy.

## Observações
- O login atual é demo (usuários estáticos). Para usar Firebase Auth, integre `signInWithEmailAndPassword` e `onAuthStateChanged`.
- Para alertas por e-mail em produção, recomendamos Firebase Cloud Functions + SendGrid.


---
Sistema gerado sob pedido de Andressa Araújo - Allrede Telecom
