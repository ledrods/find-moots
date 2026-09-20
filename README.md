<div align="center">

# 🔍 Quem não te segue de volta

**Descubra quem você segue no Instagram e não te segue de volta.**
Sem login, sem senha, sem servidor.

[![Acessar o site](https://img.shields.io/badge/acessar_o_site-2F4FE0?style=for-the-badge)](https://ledrods.github.io/find-moots/)
![Sem backend](https://img.shields.io/badge/100%25-no_navegador-1E8E6E?style=for-the-badge)
![HTML único](https://img.shields.io/badge/1-arquivo_html-16213A?style=for-the-badge)

</div>

---

## Como funciona

Você baixa o arquivo oficial de dados do Instagram e envia aqui. A página lê as listas de **seguidores** e **seguindo** e compara os dois conjuntos direto no seu navegador.

```
seguindo − seguidores  →  não te seguem de volta
seguidores − seguindo  →  você não segue de volta
seguidores ∩ seguindo  →  mútuos
```

Nada sai do seu aparelho: não existe servidor, banco de dados ou upload. Dá para desligar a internet depois que a página carregar e ainda funciona.

## Recursos

| | |
|---|---|
| 🧭 | Tutorial em 5 passos, cada um expande só se você tiver dúvida |
| 🔒 | Não pede senha do Instagram em momento nenhum |
| 📱 | Responsivo, feito para usar no celular |
| ✏️ | Botão para riscar perfis já resolvidos, salvo no seu aparelho |
| 📋 | Filtro de busca, copiar lista e exportar CSV |
| 🌓 | Tema claro e escuro automático |

## Usando

1. Instagram → **Central de Contas** → **Suas informações e permissões** → **Exportar suas informações**
2. Exportar **para o dispositivo**, em **Personalizar informações** deixe marcado apenas **Seguidores e seguindo**
3. Em **Intervalo de datas**, escolha **Desde o início** ⚠️
4. Aguarde o e-mail com o link e envie o `.zip` no site

> [!WARNING]
> O passo 3 é o que mais gera confusão. O padrão do Instagram é "Último ano", e nesse caso seus seguidores antigos ficam de fora do arquivo e aparecem por engano como quem não te segue. O site avisa quando detecta um arquivo incompleto.

## Privacidade

Ferramentas que pedem seu usuário e senha para "ver quem te deixou de seguir" podem derrubar sua conta e roubar seu acesso. Aqui o dado vem do próprio Instagram, pelo canal oficial, e é processado localmente. O código está todo neste repositório, em um único `index.html` legível.

## Rodando localmente

Basta abrir o `index.html` no navegador. Sem build, sem dependências para instalar.

---

<div align="center">
<sub>Projeto pessoal, sem vínculo com a Meta ou com o Instagram.</sub>
</div>
