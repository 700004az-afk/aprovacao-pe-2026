# Aprovação PE 2026 — aplicativo inicial

Aplicativo multiplataforma em Expo/React Native, com interface inspirada na arte enviada.

## O que já está incluído
- Painel inicial com os cargos da arte: PCPE, PMPE, CBMPE, Soldado PMPE e Oficial PMPE.
- Edital/disciplinas organizados por cargo (estrutura inicial para revisão).
- Banco demonstrativo de questões comentadas e filtro por cargo/disciplina.
- Simulado, correção automática, resultados locais, desempenho e revisão de questões favoritas/erradas.
- Ranking demonstrativo local (não é ranking online real).
- Persistência local no dispositivo via AsyncStorage.
- Interface preparada para Android e iOS.

## Executar
Requisitos: Node.js LTS e Expo.

```bash
npm install
npx expo start
```

Leia o QR code com Expo Go para testar no celular.

## Gerar builds
- Android: configure uma conta no Expo Application Services (EAS) e execute `npx eas build -p android`.
- iOS: execute `npx eas build -p ios` (é necessária conta Apple Developer para distribuição pela App Store).
- Para publicar nas lojas, configure identificador do app, ícones, política de privacidade, credenciais e revise o conteúdo.

## Importante sobre os conteúdos
Os cargos, bancas e disciplinas estão organizados como uma base inicial, não como reprodução oficial integral de editais. Confira cada edital oficial vigente antes de estudar ou publicar. Questões incluídas são demonstrativas/originais, não questões oficiais. O app funciona offline; cadastro seguro, sincronização entre dispositivos e ranking online real exigem backend e configuração de credenciais, que não são incluídos neste protótipo.
