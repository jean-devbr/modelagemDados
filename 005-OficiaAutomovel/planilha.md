# Oficina Automóvel

## CLIENTE
| ID_CLIENTE | NOME    | ENDERECO    | TELEFONE |
|------------|---------|-------------|----------|
| 1          | JEAN    | RUA TALTAL  | 21593322 |
| 2          | MICHELE | RUA JAVATA  | 31121242 |

## VEÍCULO
| ID_VEICULO | PLACA   | DATA     | ID_MARCAR | ID_CLIENTE |
|------------|---------|----------|-----------|------------|
| 1001       | SKS-J52 | 10/05/25 | 100       | 1          |
| 1002       | S9S-KPQ | 15/09/25 | 102       | 2          |

## MARCAR
| ID_MARCAR | MODELO |
|-----------|--------|
| 100       | SIENA  |
| 102       | GOL    |

## FUNCIONÁRIO
| ID_FUNCIONARIO | NOME     | TELEFONE | ENDERECO        | ID_CATEGORIA |
|----------------|----------|----------|-----------------|--------------|
| 5000           | GILBERTO | 653121   | RUA JOAO        | 20           |
| 6000           | ROBERTA  | 1212186  | RUA SEBASTIAO   | 35           |

## CATEGORIA
| ID_CATEGORIA | TIPO |
|--------------|------|
| 20           | A    |
| 35           | B    |

## PEÇA
| ID_PECA | ID_DESIGNACAO | PRECO_UNITARIO | QUANTIDADE |
|---------|---------------|----------------|------------|
| 463     | 77            | R$ 30,00       | 10         |
| 313     | 96            | R$ 50,00       | 20         |

## DESIGNAÇÃO
| ID_DESIGNACAO | DESCRICAO    |
|---------------|--------------|
| 77            | FILTRO_OLEO  |
| 96            | RODA         |

## CONSERTAR
| DURACAO | PRECO     | ID_FUNCIONARIO | ID_VEICULO |
|---------|-----------|----------------|------------|
| 2 HORAS | R$ 600,00 | 5000           | 1002       |
| 6 HORAS | R$ 500,00 | 6000           | 1001       |

## MATERIAL
| ID_FUNCIONARIO | ID_PECA |
|----------------|---------|
| 6000           | 463     |
| 5000           | 313     |