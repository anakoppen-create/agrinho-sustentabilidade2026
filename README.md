# agrinho-sustentabilidade2026
eco-reuse/
├── README.md
├── docs/
│   └── guia-reciclagem.md
├── data/
│   └── materiais-reciclaveis.csv
└── src/
    └── calculadora-residuos.py
    # ♻️ EcoReuse

Projeto open source focado em reciclagem e reaproveitamento de materiais.

## Objetivo

Promover práticas sustentáveis através da educação ambiental e do compartilhamento de recursos sobre reciclagem.

## Como usar
como eu crio o repositorio? 
- Leia o guia em `docs/guia-reciclagem.md`
- Explore os dados em `data/materiais-reciclaveis.csv`
- Teste a calculadora em `src/calculadora-residuos.py`

## Como contribuir

1. Faça um Fork
2. Crie uma Branch
3. Faça suas alterações
4. Envie um Pull Request

## Licença

MIT
# Guia de Reciclagem

## Papel
- Jornais
- Revistas
- Caixas de papelão

## Plástico
- Garrafas PET
- Embalagens plásticas limpas

## Vidro
- Garrafas
- Potes

## Metal
- Latas de alumínio
- Tampas metálicas
- Material,Categoria,Reciclavel
Papel,Jornais e Revistas,Sim
Plástico,Garrafa PET,Sim
Vidro,Garrafas,Sim
Metal,Latas de Alumínio,Sim
Papel Higiênico,Papel,Não
# Calcula impacto da reciclagem
peso = float(input("Quantidade de resíduos reciclados (kg): "))

co2_evitado = peso * 1.5  # estimativa simples

print(f"Você evitou aproximadamente {co2_evitado} kg de CO₂.")
