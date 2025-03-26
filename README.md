```markdown
# 📊 Folha de Pagamento Municipal - Amargosa/BA

**Sistema moderno de gestão financeira para administração pública**  
🔗 [Acesse a aplicação](https://folhaamargosa.vercel.app/)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Next.js](https://img.shields.io/badge/Next.js-14.2.3-black.svg)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3.3-blue.svg)](https://www.typescriptlang.org/)

---

## 🌟 Funcionalidades Principais

### � Gestão de Folhas
- Cadastro/Edição com histórico de versões
- Exclusão segura com confirmação
- Validação em tempo real de dados

### 🧮 Cálculos Automatizados
- **INSS/IRRF** com regras atualizadas
- Cálculo líquido instantâneo
- Percentuais personalizáveis por categoria

### 📊 Análise Avançada
- Dashboard interativo com Recharts
- Filtros por secretaria/período/valor
- Tabelas com paginação e ordenação

### 📤 Exportação de Dados
- Geração de PDF profissional (React-PDF)
- Exportação CSV para análise externa
- Pré-visualização de relatórios

### 🔐 Backup Seguro
- Backup manual/automático em JSON
- Restauração com verificação de integridade
- Criptografia local de dados sensíveis

---

## 🛠 Stack Tecnológica

| Camada          | Tecnologias                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| **Frontend**    | Next.js 14, TypeScript 5, React 18                                         |
| **Estilização** | Tailwind CSS 3, Shadcn/UI, CSS Modules                                     |
| **Visualização**| Recharts 2.8, React-PDF 7.7                                               |
| **Armazenamento**| LocalStorage API, IndexedDB                                               |
| **Testes**      | Jest 29, React Testing Library 14                                         |

---

## ⚙️ Instalação Local

```bash
git clone https://github.com/seu-usuario/folha-pagamento-municipal.git
cd folha-pagamento-municipal
npm install
npm run dev
```

Acesse `http://localhost:3000` no navegador

---

## 🖥 Como Utilizar

1. **Cadastrar Folha**
   ```typescript
   interface FolhaPagamento {
     nome: string;
     cargo: string;
     salarioBruto: number;
     descontos: Desconto[];
     // ... outros campos
   }
   ```
   - Preencha o formulário com validação automática
   - Visualize cálculos em tempo real

2. **Análise de Dados**
   - Utilize filtros combinados:
     ```bash
     Secretaria: Saúde
     Período: Jan/2024 - Mar/2024
     Valor Mínimo: R$ 2.500,00
     ```
   - Interaja com gráficos (hover, zoom, export)

3. **Backup Seguro**
   ```javascript
   // Exemplo de estrutura de backup
   {
     version: "1.2.0",
     timestamp: "2024-07-20T15:00:00Z",
     data: EncryptedLocalStorageData,
     checksum: "a1b2c3d4e5"
   }
   ```

---

## 🚧 Roadmap 2024-2025

### Q3 2025
- [ ] Autenticação com RBAC
- [ ] Sincronização com Supabase
- [ ] Módulo de Férias/13º

### Q4 2025
- [ ] Simulador de Cenários
- [ ] Integração Ponto Eletrônico
- [ ] Painel Administrativo

### 2026
- [ ] IA para Anomalias
- [ ] Mobile App Offline
- [ ] Multi-Município

---

## 🧪 Testes & Qualidade

```bash
# Executar testes unitários
npm test

# Gerar coverage report
npm test -- --coverage
```

**Cobertura Atual:**
- Componentes: 85%
- Serviços: 92%
- Utilitários: 100%

---

## 🤝 Contribuição

1. Fork do repositório
2. Crie sua feature branch:
   ```bash
   git checkout -b feat/nova-funcionalidade
   ```
3. Siga as diretrizes de código:
   - TypeScript estrito
   - Documentação JSDoc
   - Testes unitários
4. Submeta um Pull Request

---

## 📜 Licença

MIT License - Consulte [LICENSE](LICENSE) para detalhes

---

## 📞 Suporte

[![GitHub Issues](https://img.shields.io/github/issues/tarcinwth/FolhaDePagamento)](https://github.com/tarcinwth/FolhaDePagamento/issues)
[![Email](https://img.shields.io/badge/Email-tarciio.spotify@gmail.com-blue)](mailto:tarciio.spotify@gmail.com)


