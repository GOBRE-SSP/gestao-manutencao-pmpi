# Gestão de Manutenção Predial — PM-PI

Sistema web simples de acompanhamento de manutenção predial. **Sem servidor, sem banco de dados** — tudo roda no navegador com dados salvos localmente.

## 🎯 Características

✅ **Sem Backend Necessário** — Funciona 100% offline  
✅ **Dados Locais** — Salvos no navegador (localStorage)  
✅ **Responsivo** — Desktop, tablet e mobile  
✅ **Gráficos Interativos** — Chart.js integrado  
✅ **Exportação CSV** — Baixe relatórios facilmente  
✅ **Pronto para Produção** — Deploy em 2 minutos no Vercel  

---

## 🚀 Colocar Online em 5 Minutos

### Passo 1: Criar Repositório GitHub

1. Acesse [https://github.com/new](https://github.com/new)
2. Preencha:
   - **Repository name**: `gestao-manutencao-pmpi`
   - **Description**: `Sistema de gestão de manutenção predial PM-PI`
   - **Public**: ✓
3. Clique "Create repository"

### Passo 2: Enviar Código

```bash
# Criar pasta local
mkdir gestao-manutencao-pmpi
cd gestao-manutencao-pmpi

# Copiar 5 arquivos para aqui:
# - index.html
# - package.json
# - vercel.json
# - .gitignore
# - README.md

# Enviar para GitHub
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/SEU_USUARIO/gestao-manutencao-pmpi.git
git branch -M main
git push -u origin main
```

### Passo 3: Publicar no Vercel

1. Acesse [https://vercel.com](https://vercel.com)
2. Clique "New Project"
3. Selecione seu repositório no GitHub
4. Clique "Deploy"

**Pronto!** Seu site está online em segundos! 🎉

---

## 💾 Dados

Os dados são salvos **no navegador** (localStorage):
- Cada navegador tem seus próprios dados
- Dados persistem entre sessões
- Não sincroniza entre dispositivos
- **Backup**: exporte CSV regularmente

---

## 📝 Como Usar

1. **Nova Obra** → Clique "Nova obra"
2. **Expandir** → Clique em uma obra para ver detalhes
3. **Adicionar Medição** → Clique "Adicionar medição"
4. **Editar** → Clique no lápis
5. **Exportar** → Clique "Exportar CSV"

---

## 🔄 Atualizar Código

```bash
git add .
git commit -m "Sua mudança"
git push
```

Vercel faz deploy automático!

---

## ❓ Dúvidas

**P: Meus dados desaparecem se limpar cache?**  
R: Sim. Exporte CSV regularmente como backup.

**P: Posso compartilhar com outras pessoas?**  
R: Cada pessoa tem seus próprios dados. Para compartilhar, exporte CSV e envie.

**P: Posso adicionar banco de dados?**  
R: Sim! Integre Firebase, Supabase ou qualquer outro API.

**P: Quanto custa?**  
R: Gratuito! Vercel oferece hospedagem grátis.

---

**Pronto para usar! 🚀**

---

*Versão 1.0.0 — Junho 2026*
