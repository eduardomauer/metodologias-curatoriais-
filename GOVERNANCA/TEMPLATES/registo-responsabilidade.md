# Template — Registo de Responsabilidade

```yaml
registo_responsabilidade:
  id: MILK-RESP-YYYYMMDD-0001
  data: YYYY-MM-DD
  objeto:
    tipo: artefacto | pacote | release
    ids: [ATLAS-...]
  declaracao:
    frase_gatilho_obrigatoria: "validação e assinatura diário"
    autorizacao_publicacao: sim | não
  responsavel_soberano:
    nome: [não especificado]
    identificador: [não especificado]
  assinaturas:
    - nome: []
      metodo: assinatura manuscrita | assinatura digital qualificada | outro
      timestamp: []
  integridade:
    algoritmo: SHA-256
    hashes:
      - ficheiro: [nome]
        hash: []
```
