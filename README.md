# Power BI - Visualização de Empreendimentos

Este projeto fornece uma interface web para visualizar dashboards do Power BI com foco em empreendimentos específicos.

## Como Usar

### Acesso Básico
Para acessar o dashboard geral:
```
index.html
```

### Acesso com Empreendimento Específico
Para visualizar um empreendimento específico, use o parâmetro `id_empreendimento` na URL:

```
index.html?id_empreendimento=123
```

## Funcionalidades

### Parâmetros URL Suportados

| Parâmetro | Descrição | Exemplo |
|-----------|-----------|---------|
| `id_empreendimento` | ID do empreendimento a ser destacado | `?id_empreendimento=123` |

### Comportamento da Página

1. **Sem parâmetro:** A página carrega o dashboard normalmente sem instruções específicas
2. **Com parâmetro:** A página exibe uma instrução destacada informando qual empreendimento filtrar no Power BI

## Tecnologias Utilizadas

- **HTML5:** Estrutura da página
- **CSS3:** Estilização e design responsivo
- **JavaScript:** Lógica de parâmetros URL e controle do iframe
- **Power BI:** Dashboard embeddado

## Configuração do Power BI

O dashboard está configurado para carregar a partir da URL:
```
https://app.powerbi.com/view?r=eyJrIjoiN2RmNTdlYWItOWJjMi00YjE2LThhZjYtZDhmZmNlM2Y4YTI4IiwidCI6ImZjNWJlNzgyLWM2MTktNGM2Ni05M2ExLWExNmNiMjNjMzhmOSJ9&pageName=4ed15a60a7e9c1b03cb0
```

## Acesso Online

O projeto está hospedado no GitHub Pages e pode ser acessado através do link:

**🔗 Link Principal:** https://dicop-codemge.github.io/power-bi-peltcp-empreendimentos/

### Exemplos de Uso Online

- **Empreendimento específico:** https://dicop-codemge.github.io/power-bi-peltcp-empreendimentos/?id_empreendimento=11
