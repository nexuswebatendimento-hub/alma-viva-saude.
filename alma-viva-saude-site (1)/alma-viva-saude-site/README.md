# Alma Viva Saúde (site modelo)

Site estático em um único arquivo (`index.html`), sem build e sem dependências.

## Configurar
No fim do `index.html`, no bloco `CONFIGURAÇÃO`, preencha:
- `WHATSAPP`: 55 + DDD + número, só números (ex.: 5511912345678)
- `ENDERECO`: endereço completo (ativa o mapa e o botão do Google Maps)
- `HORARIO`: dias e horários de atendimento
- `FOTOS`: caminhos das fotos reais (pasta `img`). Sem foto, aparecem as ilustrações.

Depois troque os textos entre colchetes (serviços, equipe, sobre, FAQ, rodapé) e os depoimentos reais.

## Publicar
1. GitHub: crie um repositório e envie estes arquivos na raiz.
2. Vercel: Add New > Project > importe o repositório. Framework: Other. Sem comando de build; diretório de saída: raiz.
