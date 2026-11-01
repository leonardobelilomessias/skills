# Skills para Agentes de IA

Repositório pessoal de **Skills** reutilizáveis para agentes de inteligência artificial (compatível com Google Antigravity, Claude Code, Cursor, Superpowers e outros assistentes baseados em agentes).

---

## 📦 Skills Disponíveis

| Skill | Descrição | Status |
|---|---|---|
| [`roteiro-video`](./roteiro-video/SKILL.md) | Edita e transforma textos, rascunhos ou ideias em roteiros profissionais de vídeo prontos para gravação, aplicando gatilhos mentais naturais e checagem de dados reais. | ✅ Ativa |

---

## 🎬 Detalhes da Skill: `roteiro-video`

A skill **`roteiro-video`** atua como um editor especializado em roteiros de alta retenção e conversão (Reels, TikTok, YouTube, Shorts, VSL e vídeos educativos).

### Principais Características
- **Baseada em fatos reais:** Não inventa números, depoimentos ou dados que possam expor o criador a riscos de credibilidade ou jurídicos.
- **Checagem de dados públicos:** Quando oportuno, pesquisa estatísticas e indicadores em órgãos oficiais (IBGE, Banco Central, Receita, etc.) registrando a fonte e data.
- **Saída Dupla Padronizada:**
  1. **Versão Anotada:** Exibe os gatilhos mentais aplicados (`[Gatilho]`), destacando trechos novos e reescritos.
  2. **Versão Limpa:** Texto contínuo e fluído pronto para o teleprompter ou gravação direta.

---

## 🚀 Como Utilizar

### 1. No Google Antigravity
Você pode copiar a pasta da skill para seu diretório de skills local ou do projeto:

```bash
# No diretório do projeto:
mkdir -p .agents/skills/roteiro-video
curl -sSL https://raw.githubusercontent.com/leonardobelilomessias/skills/main/roteiro-video/SKILL.md -o .agents/skills/roteiro-video/SKILL.md
```

Ou clonar este repositório diretamente:
```bash
git clone https://github.com/leonardobelilomessias/skills.git
```

### 2. No Claude Code / Cursor / Agentes Customizados
Copie o conteúdo de [`roteiro-video/SKILL.md`](./roteiro-video/SKILL.md) para as instruções de sistema (system prompt), prompt de contexto ou pasta `.cursorrules` / `.claude/skills`.

---

## 📄 Licença

Distribuído sob a licença [MIT](./LICENSE).
