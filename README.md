# BuscaCupom - Sistema de Download de NFCe

[![Versao](https://img.shields.io/badge/versao-1.0.1-blue.svg)](https://github.com/daniloconsult/NFCeDownloader-Releases/releases/latest)
[![Plataforma](https://img.shields.io/badge/plataforma-Windows-lightgrey.svg)](https://github.com/daniloconsult/NFCeDownloader-Releases/releases)
[![.NET](https://img.shields.io/badge/.NET-8.0-purple.svg)](https://dotnet.microsoft.com/)

## Download da Ultima Versao

**[⬇️ Baixar v1.0.1 (91.26 MB)](https://github.com/daniloconsult/NFCeDownloader-Releases/releases/download/v1.0.1/BuscaCupom-v1.0.1.zip)**

---

## Sobre o Sistema

Sistema profissional para download e gerenciamento de Notas Fiscais Eletronicas (NFCe) com suporte multi-empresa.

### Principais Recursos

- **Multi-Tenant:** Gerenciamento de multiplas empresas
- **Controle de Usuarios:** Sistema de permissoes por empresa
- **Autenticacao Segura:** Criptografia BCrypt
- **Painel Administrativo:** Gestao completa de empresas, licencas e usuarios
- **Interface Moderna:** Material Design
- **Cloud Database:** Supabase (PostgreSQL)
- **Sessoes Controladas:** Limite de usuarios simultaneos por licenca

---

## Requisitos do Sistema

- **Windows:** 10 ou 11 (64-bit)
- **Espaco em Disco:** ~100 MB
- **Memoria RAM:** Minimo 2 GB
- **Internet:** Conexao ativa (para acesso ao banco de dados)

**Nao e necessario instalar .NET** - o executavel ja inclui tudo que precisa!

---

## Como Instalar

1. Acesse a pagina de [**Releases**](https://github.com/daniloconsult/NFCeDownloader-Releases/releases)
2. Baixe o arquivo **ZIP** da ultima versao
3. Extraia o arquivo para uma pasta de sua preferencia
4. Execute o arquivo `BuscaCupom.exe`

### Primeira Execucao

- Windows pode exibir "Windows protegeu seu PC"
- Clique em **"Mais informacoes"** → **"Executar assim mesmo"**
- Execute como **Administrador** (botao direito → Executar como administrador)

---

## Configuracao

### 1. Arquivo de Configuracao
Na primeira execucao, sera criado o arquivo `Config.json` na mesma pasta do executavel.

### 2. Credenciais Supabase
Se voce e administrador do sistema, configure o `Config.json`:

```json
{
  "SupabaseUrl": "https://seu-projeto.supabase.co",
  "SupabaseKey": "sua-chave-anon-aqui"
}
```

**Usuarios finais:** Entre em contato com o administrador para obter as credenciais.

---

## Login Padrao

### Conta de Desenvolvedor:
- **Usuario:** `dev`
- **Senha:** `dev123`

### Conta Administrativa:
- **Usuario:** `admin`
- **Senha:** `admin123`

**Importante:** Altere as senhas padrao apos o primeiro login!

---

## Novidades v1.0.1

### Melhorias na Interface
- Corrigido encoding da tela de Administracao
- Melhorada responsividade dos botoes (efeito hover)
- Ajustados bindings das grids
- Corrigido texto de status da licenca

### Correcoes de Bugs
- Botoes de Usuario agora funcionam corretamente
- Aba Sessoes Ativas mostra login do usuario
- Contador de usuarios online atualiza corretamente
- Desconectar sessao funcionando perfeitamente

---

## Suporte

### Problemas Comuns

#### "Erro ao conectar com banco de dados"
- Verifique sua conexao com a internet
- Confirme que o arquivo `Config.json` esta configurado corretamente
- Valide as credenciais do Supabase

#### "Licenca vencida"
- Entre em contato com o administrador do sistema
- Verifique a data de vencimento da licenca da sua empresa

#### "Sessoes simultaneas excedidas"
- Sua empresa atingiu o limite de usuarios simultaneos
- Aguarde outro usuario encerrar a sessao
- Ou solicite upgrade da licenca

---

## Historico de Versoes

### v1.0.1 (Atual)
- Correcoes de interface e bugs
- Melhorias de responsividade

### v1.0.0
- Lancamento inicial
- Sistema multi-tenant completo

Veja todas as versoes na pagina de [**Releases**](https://github.com/daniloconsult/NFCeDownloader-Releases/releases).

---

## Privacidade e Seguranca

- Senhas criptografadas com BCrypt
- Comunicacao segura via HTTPS
- Banco de dados em nuvem confiavel (Supabase)
- Logs de acesso para auditoria
- Controle de sessoes simultaneas

---

## Contato

Para duvidas, sugestoes ou reportar problemas:
- **Issues:** [Abrir ticket](https://github.com/daniloconsult/NFCeDownloader-Releases/issues)

---

<div align="center">

**Desenvolvido com .NET 8 + WPF + Supabase**

[⬇️ Baixar Agora](https://github.com/daniloconsult/NFCeDownloader-Releases/releases/latest) | [📋 Todas as Versoes](https://github.com/daniloconsult/NFCeDownloader-Releases/releases) | [🐛 Reportar Bug](https://github.com/daniloconsult/NFCeDownloader-Releases/issues)

</div>
