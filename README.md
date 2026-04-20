# NFCe Downloader - Downloads

## 📥 Última Versão

[**⬇️ Baixar Versão Mais Recente**](../../releases/latest)

---

## 🚀 O que é?

Sistema profissional para download e gerenciamento de Notas Fiscais Eletrônicas (NFCe) com suporte multi-empresa.

### ✨ Principais Recursos:
- 🏢 **Multi-Tenant**: Gerenciamento de múltiplas empresas
- 👥 **Controle de Usuários**: Sistema de permissões por empresa
- 🔐 **Autenticação Segura**: Criptografia BCrypt
- 📊 **Painel Administrativo**: Gestão completa de empresas, licenças e usuários
- 🎨 **Interface Moderna**: Material Design
- 💾 **Cloud Database**: Supabase (PostgreSQL)

---

## 💻 Requisitos do Sistema

- **Windows**: 10 ou 11 (64-bit)
- **Espaço em Disco**: ~100 MB
- **Memória RAM**: Mínimo 2 GB
- **Internet**: Conexão ativa (para acesso ao banco de dados)

> ℹ️ **Não é necessário instalar .NET** - o executável já inclui tudo que precisa!

---

## 🔧 Como Instalar

1. Acesse a página de [**Releases**](../../releases)
2. Baixe o arquivo **ZIP** da última versão
3. Extraia o arquivo para uma pasta de sua preferência
4. Execute o arquivo `NFCeDownloader.exe`

### ⚠️ Primeira Execução
- Windows pode exibir "Windows protegeu seu PC"
- Clique em **"Mais informações"** → **"Executar assim mesmo"**
- Execute como **Administrador** (botão direito → Executar como administrador)

---

## ⚙️ Configuração

### 1. Arquivo de Configuração
Na primeira execução, será criado o arquivo `Config.json` na mesma pasta do executável.

### 2. Credenciais Supabase
Se você é administrador do sistema, configure o `Config.json`:

```json
{
  "SupabaseUrl": "https://seu-projeto.supabase.co",
  "SupabaseKey": "sua-chave-anon-aqui"
}
```

> ⚠️ **Usuários finais**: Entre em contato com o administrador para obter as credenciais.

---

## 🔑 Login Padrão

### Conta de Desenvolvedor:
- **Usuário**: `dev`
- **Senha**: `dev123`

> ⚠️ **Importante**: Altere a senha padrão após o primeiro login!

---

## 🆘 Suporte

### Problemas Comuns

#### ❌ "Erro ao conectar com banco de dados"
- Verifique sua conexão com a internet
- Confirme que o arquivo `Config.json` está configurado corretamente
- Valide as credenciais do Supabase

#### ❌ "Licença vencida"
- Entre em contato com o administrador do sistema
- Verifique a data de vencimento da licença da sua empresa

#### ❌ "Sessões simultâneas excedidas"
- Sua empresa atingiu o limite de usuários simultâneos
- Aguarde outro usuário encerrar a sessão
- Ou solicite upgrade da licença

---

## 📋 Histórico de Versões

Veja todas as versões e mudanças na página de [**Releases**](../../releases).

---

## 🔒 Privacidade e Segurança

- ✅ Senhas criptografadas com BCrypt
- ✅ Comunicação segura via HTTPS
- ✅ Banco de dados em nuvem confiável (Supabase)
- ✅ Logs de acesso para auditoria
- ✅ Controle de sessões simultâneas

---

## 📞 Contato

Para dúvidas, sugestões ou reportar problemas:
- 📧 Email: [seu-email@exemplo.com]
- 🐛 Issues: [Abrir ticket](../../issues)

---

<div align="center">

**Desenvolvido com ❤️ usando .NET 8 + WPF + Supabase**

[⬇️ Baixar Agora](../../releases/latest) | [📖 Documentação](../../wiki) | [🐛 Reportar Bug](../../issues)

</div>
