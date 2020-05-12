# Mostruario Service

[Link Swagger Mostruario-Service](http://swaggerdimed/?url=http://tst.grupodimedservices.com.br/mostruario/swagger.json#/)
Obs.: usar em navegador sem proxy

[Link Wiki Services](http://wikiservices/index.php/Portf%C3%B3lio_de_Servi%C3%A7os)
Obs.: usar em navegador sem proxy

## Conteúdo
* [Mostruario Service](#Mostruario_Service)
   * [URL](#url)
   * [Github](#github)
   * [Swagger](#swagger)
   * [Proxy](#proxy)   
   * [I. Operações de Itens](#i-operações-de-itens)
      * [1 Busca por código de barras](#1-busca-por-código-de-barras)
      * [2 Operação para detalhamento de uma lista de itens](#2-operação-para-detalhamento-de-uma-lista-de-itens)
        * [Request (default)](#request(default))
        * [Filtros](#filtros)
        * [2.1.1 advertencias](#211-advertencias)
        * [2.1.2 alternativos](#212-alternativos)
        * [2.1.3 videos](#213-videos)
        * [2.1.4 participa-novo-pack](#214-participa-novo-pack)
        * [2.1.5 preco-base](#215-preco-base)
        * [2.1.6 bula](#216-bula)
        * [2.1.7 categorias](#217-categorias)
        * [2.1.8 dados-imagem](#218-dados-imagem)
        * [2.1.9 possui-ean-impresso](#219-possui-ean-impresso)
        * [2.1.10 preco-final](#2110-preco-final)
        * [2.1.11 principio-ativo](#2111-principio-ativo)
        * [2.1.12 promocao](#2112-promocao)
        * [2.1.13 regras-fiscais](#2113-regras-fiscais)
        * [2.1.14 possui-genericos](#2114-possui-genericos)
        * [2.1.15 possui-iav](#2115-possui-iav)
        * [2.1.16 lancamento](#2116-lancamento)
        * [2.1.17 desconto-pack](#2117-desconto-pack)
        * [2.1.18 desconto-pbm](#2118-desconto-pbm)
        * [2.1.19 restricoes](#2119-restricoes)
        * [2.1.20 gera-dados-fornecedor](#2120-gera-dados-fornecedor)
        * [2.1.21 multiatendimento](#2121-multiatendimento)
        * [2.1.22 convenio](#2122-convenio)
        * [2.1.23 ean](#2123-ean)
        * [2.1.24 possui-similares](#2124-possui-similares)
        * [2.1.25 bloqueados-internet](#2125-bloqueados-internet)
        * [2.1.26 descricao-detalhada](#2126-descricao-detalhada)
        * [2.1.27 venda-liberada](#2127-venda-liberada)
        * [2.1.28 codigo-fabricante](#2128-codigo-fabricante)
        * [2.1.29 tipo-item](#2129-tipo-item)
        * [2.1.30 nomenclatura](#2130-nomenclatura)
        * [2.1.31 psicotropico](#2131-psicotropico)
        * [2.1.32 retencao-receita](#2132-retencao-receita)
        * [2.1.33 otc](#2133-otc)
        * [2.1.34 custo-medio](#2134-custo-medio)
        * [2.1.35 marca-pai](#2135-marca-pai)
        * [2.1.36 uso-continuo](#2136-uso-continuo)
        * [2.1.37 cupom-oferta](#2137-cupom-oferta)
        * [2.1.38 situacao-item](#2138-situacao-item)
        * [2.1.39 classe-terapeutica](#2139-classe-terapeutica)
        * [2.1.40 adesao](#2140-adesao)
        * [2.1.41 exclusivo-panvel](#2141-exclusivo-panvel)
        * [2.1.42 item-geladeira](#2142-item-geladeira)
        * [2.1.43 participa-lista-referencial](#2143-participa-lista-referencial)
        * [2.1.44 participa-farmacia-popular](#2144-participa-farmacia-popular)
        * [2.1.45 item-assinavel](#2145-item-assinavel)
        * [2.1.46 promocao-assinatura](#2146-promocao-assinatura)
        * [2.1.47 desconto-iav](#2147-desconto-iav)
        * [2.1.48 quantidade-apresentacao](#2148-quantidade-apresentacao)
        * [2.1.49 participa-pbm](#2149-participa-pbm)
        * [2.1.50 categoria](#2150-categoria)
        * [2.1.51 descontos](#2151-descontos)
        * [2.1.52 preco-unitizavel](#2152-preco-unitizavel)
        * [2.1.53 rentabilidade](#2153-rentabilidade)
        * [2.1.54 eans-alternativos](#2154-eans-alternativos)
        * [2.1.55 presenteavel](#2155-presenteavel)
        * [2.1.56 default](#2156-default)     
      * [3 Listagem de itens](#3-listagem-de-itens)
      * [4 Detalhamento de informações de uma lista de itens](#4-detalhamento-de-informações-de-uma-lista-de-itens)
      * [5 Buscar itens alternativos a partir de um código do item](#5-buscar-itens-alternativos-a-partir-de-um-código do-item)
      * [6 Buscar itens genéricos a partir de um item](#6-buscar-itens-genéricos-a-partir-de-um-item)
      * [7 Buscar itens a partir de um princípio ativo](#7-buscar-itens-a-partir-de-um-princípio-ativo)
      * [8 Buscar itens referência a partir de um código do item](#8-buscar-itens-referência-a-partir-de-um-código-do-item)
      * [9 Buscar itens similares a partir de um item](#9-buscar-itens-similares-a-partir-de-um-item)

## URL
LOCAL: [http://localhost:9006/mostruario/v3/](http://localhost:9006/mostruario/v3/)

TST: [http://thabittst1.dimed.com.br:9006/mostruario/v3/](http://thabittst1.dimed.com.br:9006/mostruario/v3/)

## Github
URL:
[https://github.com/tigrupodimed/mostruario-service](https://github.com/tigrupodimed/mostruario-service)

## Swagger
LOCAL:
[http://localhost:9006/mostruario/swagger.json](http://thabittst1.dimed.com.br:9006/mostruario/swagger.json)

TST: [http://thabittst1.dimed.com.br:9006/mostruario/swagger.json](http://thabittst1.dimed.com.br:9006/mostruario/swagger.json)

## Proxy
vm options :
[-Dhttp.proxyHost=proxyweb.dimed.com.br -Dhttp.proxyPort=8080 -Dhttps.proxyHost=proxyweb.dimed.com.br -Dhttps.proxyPort=8080 -Dcom.sun.net.ssl.checkRevocation=false -Djavax.net.ssl.trustStore=/usr/lib/jvm/java-8-oracle/jre/lib/security/cacerts

## I. Operações de Itens
------------
### 1. Busca por código de barras

- GET http://localhost:9006/mostruario/v3​/itens/barcode=7892828000019?cep=91110020&quantidade=1

- Response
```
{
  "codItem": 27,
  "codTipoItem": 1,
  "categoria": "V",
  "codFilial": 31,
  "vendaLiberada": true,
  "nomenclatura": "ADEFORTE 1AMPX3ML",
  "permiteDesconto": true,
  "precoDe": 11.75,
  "precoPor": 11.75,
  "classeTerapeutica": "POLIVITAMINICOS",
  "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
  "origemDesconto": "PROMOCAO",
  "valorTotal": 11.75,
  "quantidade": 1,
  "psicotropico": false,
  "retencaoReceita": false,
  "isLancamento": false,
  "possuiGenericos": false,
  "possuiSimilares": false,
  "possuiAlternativos": false,
  "advertencias": [
    "A persistirem os sintomas, o médico deverá ser consultado."
  ],
  "farmaciaPopular": false,
  "multiAtendimento": false,
  "dadosImagens": [
    {
      "sequenciaImagem": 29050,
      "numeroImagem": 1,
      "imagemPreferencial": "S"
    }
  ],
  "categorias": [
    {
      "id": 1,
      "descricao": "Medicamentos",
      "nivel": 1
    },
    {
      "id": 29,
      "descricao": "Visão",
      "nivel": 2
    },
    {
      "id": 24,
      "descricao": "Vitaminas e Minerais",
      "nivel": 3
    }
  ],
  "isPack": false,
  "linksVideo": [],
  "restricoes": [
    2
  ],
  "geraDadosFornecedor": false,
  "perfil": 0,
  "participaPbm": false,
  "possuiEanImpresso": true
}
```

### 2. Operação para detalhamento de uma lista de itens

- POST http://localhost:9006/mostruario/v3/itens/detalhe

#### Request(default)

```
{
  "filial": 101,                        --opcional (default 1002)
  "cep": "93010180",                    --opcional (default 1002)
  "perfil": 2,                          --obrigatorio
  "codigoCupomOfertas": 12164865,       --opcional
  "codConvenio": 0,                     --opcional
  "convenios": [                        --opcional
    {
      "codigoConvenio": 416061,         --opcional         
      "matricula": "93593161052",       --opcional
      "codigoDependente": 0             --opcional
    }
  ], 
  "itens": [
    {
      "identificador": "123",           --opcional
      "codigo": 694170,                 --obrigatorio
      "codigoIav": 11951,               --opcional
      "quantidade": 2,                  --opcional (default 1)
      "isPack": false,                  --opcional (default false)
      "descontoPack": {                 --opcional
        "perfilPack":1,                 --opcional (sera utilizado valor do perfil)
        "quantidade":3,                 --opcional (sera utilizado valor minimo para formar pack)
        "precoDe":77.24,                --opcional (sera utilizado valor do preço base)
        "precoPor":77.24                --opcional (sera utilizado valor da melhor desconto)
      }
    }
  ], 
  "consultaRegrasFiscais": {            --opcional
    "uf": "RS",                         --opcional
    "pais": "BR",                       --opcional
    "ufDestino": "RS",                  --opcional
    "paisDestino": "BR"                 --opcional
  }
}
```
#### Filtros
* Exemplo utilizando todos os filtros:
`POST http://localhost:9006/mostruario/v3/itens/detalhe?filter=categoria&filter=advertencias&filter=alternativos&filter=videos&filter=participa-novo-pack&
filter=preco-base&filter=bula&filter=categorias&filter=dados-imagem&filter=possui-ean-impresso&filter=preco-final&filter=principio-ativo&filter=promocao&
filter=descontos&filter=regras-fiscais&filter=possui-genericos&filter=possui-iav&filter=lancamento&filter=desconto-pack&filter=desconto-pbm&
filter=restricoes&filter=gera-dados-fornecedor&filter=multiatendimento&filter=convenio&filter=ean&filter=possui-similares&filter=bloqueados-internet&
filter=descricao-detalhada&filter=venda-liberada&filter=codigo-fabricante&filter=tipo-item&filter=psicotropico&filter=nomenclatura&filter=retencao-receita&
filter=possui-genericos&filter=otc&filter=custo-medio&filter=marca-pai&filter=uso-continuo&filter=cupom-oferta&filter=situacao-item&filter=classe-terapeutica&
filter=adesao&filter=exclusivo-panvel&filter=item-geladeira&filter=participa-lista-referencial&filter=participa-farmacia-popular&filter=item-assinavel&
filter=promocao-assinatura&filter=desconto-iav&filter=quantidade-apresentacao&filter=participa-pbm&filter=preco-unitizavel&filter=rentabilidade&
filter=eans-alternativos&filter=presenteavel`

* Exemplo de utilização de filtros agregados na consulta:

`POST http://localhost:9006/mostruario/v3/itens/detalhe?filter=preco-final&filter=videos`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "itens": [
        {
            "codigo": 947400
        }
    ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 947400,
            "precoDe": 30.25,
            "precoPor": 15.13,
            "origemDesconto": "PROMOCAO",
            "percentualDesconto": 49.98,
            "codigoFilial": 101,
            "linksVideo": [
                "https://www.youtube.com/embed/mEU_LZzqP8A",
                "https://www.youtube.com/embed/9rn0ni4-R6o"
            ]
        }
    ],
    "packs": []
}
```


#### 2.1.1 advertencias

- tipo: `DEFAULT`
- query param:
   `?filter=advertencias`
- request:
```
{
   "filial": 101,  
   "perfil": 1,  
   "itens": [
       {
           "identificador: "123456",
           "codigo": 305103         
       }		  
   ]  
}
```
- response:
```
{
  "itens": [
    {
      "identificador: "123456",
      "codigo": 575850,
      "codigoFilial": 101,
      "advertencias": [
        "A persistirem os sintomas, o médico deverá ser          consultado."
      ]
    }
  ],
  "packs": []
}
```

##### 2.1.1 advertencias

- tipo: `DEFAULT`
- query param:
   `?filter=alternativos`
- request:
```
{
   "perfil": 1,
   "itens": [
       {
           "codigo": 403014
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 403014,
      "codigoFilial": 101,
      "possuiAlternativos": true
    }
  ],
  "packs": []
}
```

#### 2.1.3 videos

- tipo: `DEFAULT`
- query param:
   `?filter=videos`
- request:
```
{
   "perfil": 1,
   "itens": [
       {
           "codigo": 947400
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 947400,
      "codigoFilial": 101,
      "linksVideo": [
        "https://www.youtube.com/embed/mEU_LZzqP8A",
        "https://www.youtube.com/embed/9rn0ni4-R6o"
      ]
    }
  ],
  "packs": []
}
```

#### 2.1.4 participa-novo-pack

- tipo: `DEFAULT`
- query param:
   `?filter=participa-novo-pack`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "itens": [
        {
            "codigo": 118840
        }
    ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 118840,
            "codigoFilial": 101,
            "participaPackNovo": true,
            "novoPack": {
                "codigo": 21831,
                "descricao": "NA COMPRA DE 2 FRALDA POM POM PROTEÇÃO 12H, PAGUE R$ 34,99 CADA NO PACK",
                "dataInicial": "2019-10-28",
                "dataFinal": "2021-12-31",
                "descricaoCategoria": "COMPRE {quantidade} POR {vlrunitario} CADA",
                "descricaoTag": "Leve + Pague -",
                "descricaoSite": "NA COMPRA DE 2 FRALDA POM POM PROTEÇÃO 12H, PAGUE R$ 34,99 CADA NO PACK",
                "descricaoModalidade": "BEM PANVEL REVISTA DE OFERTAS",
                "quantidadeCompra": 2,
                "bemPanvel": true
            }
        }
    ],
    "packs": []
}
```

#### 2.1.5 preco-base

- tipo: `DEFAULT`
- query param:
   `?filter=preco-base`
- request:
```
{
   "filial": 101,  
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "precoDe": 64.66,
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.6 bula

- tipo: `DEFAULT`
- query param:
   `?filter=bula`
- request:
```
{   
   "perfil": 1,   
   "itens": [
       {
           "codigo": 305103         
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "bula": "<!DOCTYPE HTML PUBLIC ...”
  ],
  "packs": []
}
```

#### 2.1.7 categorias

- tipo: `DEFAULT`
- query param:
   `?filter=categorias`
- request:
```
{   
   "perfil": 1,   
   "itens": [
       {
           "codigo": 496190         
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 496190,
      "codigoFilial": 1002,
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 25,
          "descricao": "Saúde da Mulher",
          "nivel": 2
        },
        {
          "id": 124,
          "descricao": "Anticoncepcionais",
          "nivel": 3
        }
      ]
    }
  ],
  "packs": []
}
```

#### 2.1.8 dados-imagem

- tipo: `DEFAULT`
- query param:
   `?filter=dados-imagem`
- request:
```
{   
   "perfil": 1,   
   "itens": [
       {
           "codigo": 153028         
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 27,
      "codigoFilial": 333,
      "dadosImagens": [
        {
          "sequenciaImagem": 29050,
          "numeroImagem": 1,
          "imagemPreferencial": "S",
          "url": "http://staticpanveltstnew.panvel.com/produtos/15/27-15.jpg"
        }
      ]
    }
  ],
  "packs": []
}
```

#### 2.1.9 possui-ean-impresso

- tipo: `DEFAULT`
- query param:
   `?filter=possui-ean-impresso`
- request:
```
{   
   "perfil": 1,   
   "itens": [
       {
           "codigo": 496190         
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 496190,
      "codigoFilial": 1002,
      "possuiEanImpresso": true
    }
  ],
  "packs": []
}
```

#### 2.1.10 preco-final

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=preco-final`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "convenios": [
        {
            "codigoConvenio": 416061,
            "matricula": "92052037004"
        }
    ],
    "itens": [
        {
            "codigo": 403014
        }
    ],
    "consultaRegrasFiscais": {
        "uf": "RS",
        "pais": "BR",
        "ufDestino": "RS",
        "paisDestino": "BR"
    }
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 403014,
            "precoDe": 102.72,
            "precoPor": 98.61,
            "origemDesconto": "PROMOCAO",
            "percentualDesconto": 4.0,
            "codigoFilial": 101
        }
    ],
    "packs": []
}
```

#### 2.1.11 principio-ativo

- tipo: `DEFAULT`
- query param:
   `?filter=principio-ativo`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 153028
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "codigoPrincipioAtivo": 4733,
      "principioAtivo": "PAMOATO PIRVINIO",
      "codigoFilial": 101,
      "possuiSimilaresPorPrincipioAtivo": true,
      "possuiGenericosPorPrincipioAtivo": false,
      "possuiReferenciaPorPrincipioAtivo": false
    }
  ],
  "packs": []
}
```

#### 2.1.12 promocao

- tipo: `DEFAULT`
- query param:
   `?filter=promocao`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "convenios": [
       {
           "codigoConvenio": 416061,
           "matricula": "92052037004"
       }
   ],
   "itens": [
       {
           "codigo": 153028         
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "precoDe": 25.23,
      "promocao": {
        "codigoPromocao": 72803,
        "codigoFilialPromotora": 1002,
        "perfil": 1,
        "percentualDesconto": 0.0,
        "dataInicio": "09/01/2018",
        "tipoPromocao": "Bem Panvel"
      },
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.13 regras-fiscais

- tipo: `DEFAULT`
- query param:
   `?filter=regras-fiscais`
- request:
```
{
   "filial": 101,  
   "perfil": 1,
   "itens": [
       {
           "codigo": 153028    
       }
   ],
   "consultaRegrasFiscais": {
       "uf": "RS",
       "pais": "BR",
       "ufDestino": "RS",
       "paisDestino": "BR"
   }
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "regraFiscal": {
        "codigoLegenda": 4,
        "codigoCfop": 5405,
        "codigoSituacaoTributaria": 60,
        "aliquotaIcms": 18,
        "percentualIsencao": 0.0,
        "somaIsencaoComPromocao": false
      },
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.14 possui-genericos

- tipo: `DEFAULT`
- query param:
   `?filter=possui-genericos`
- request:
```
{ 
   "filial":101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 153028
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "codigoFilial": 101,
      "possuiGenericos": false
    }
  ],
  "packs": []
}
```

#### 2.1.15 possui-iav

- tipo: `DEFAULT`
- query param:
   `?filter=advertencias`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 153028
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "codigoFilial": 101,
      "possuiItemAVencer": false
    }
  ],
  "packs": []
}
```

#### 2.1.16 lancamento

- tipo: `DEFAULT`
- query param:
   `?filter=lancamento`
- request:
```
{ 
   "perfil": 1,
   "itens": [
       {
           "codigo": 153028
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "codigoFilial": 1002,
      "lancamento": false
    }
  ],
  "packs": []
}
```

#### 2.1.17 desconto-pack

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=desconto-pack`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 496190,
           "quantidade": 3,
            "descontoPack": {
              "perfilPack":1,
              "quantidade":3,  
              "precoDe":77.24,
              "precoPor":77.24
          }
       }
   ]
}

```
- response:
```
{
    "itens": [
        {
            "codigo": 496190,
            "codigoFilial": 101,
            "novoPack": {
                "codigo": 18674,
                "descricao": "PACK ANTICONCEPCIONAL - NA COMPRA DE 1 UNID GANHE 15%, 2 UNID GANHE 20%, 3 UNID GANHE 25%",
                "dataInicial": "2019-12-02",
                "dataFinal": "2099-12-31",
                "descricaoCategoria": "2UN 20%, 3UN 25% OFF",
                "descricaoTag": "Leve + Pague -",
                "descricaoSite": "PACK ANTICONCEPCIONAL - NA COMPRA DE 1 UNID GANHE 15%, 2 UNID GANHE 20%, 3 UNID GANHE 25%",
                "descricaoModalidade": "NEGOCIAÇÕES COMERCIAL",
                "quantidadeCompra": 3
            },
            "descontoPack": 25.03
        }
    ],
    "packs": []
}
```

#### 2.1.18 desconto-pbm

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=desconto-pbm`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "convenios": [
        {
            "codigoConvenio": 416061,
            "matricula": "92052037004"
        }
    ],
    "itens": [
        {
            "codigo": 628430
        }
    ],
    "consultaRegrasFiscais": {
        "uf": "RS",
        "pais": "BR",
        "ufDestino": "RS",
        "paisDestino": "BR"
    }
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 628430,
            "percentualDescontoPbm": 57.0,
            "codigoFilial": 101,
            "participaPbm": true
        }
    ],
    "packs": []
}
```

#### 2.1.19 restricoes

- tipo: `DEFAULT`
- query param:
   `?filter=restricoes`
- request:
```
{
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "restricoes": [
        2
      ]
    }
  ],
  "packs": []
}
```

#### 2.1.20 gera-dados-fornecedor

- tipo: `DEFAULT`
- query param:
   `?filter=gera-dados-fornecedor`
- request:
```
{
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "geraDadosFornecedor": false
    }
  ],
  "packs": []
}
```

#### 2.1.21 multiatendimento

- tipo: `DEFAULT`
- query param:
   `?filter=multiatendimento`
- request:
```
{
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 1002,
      "multiAtendimento": false
    }
  ],
  "packs": []
}
```

#### 2.1.22 convenio

- tipo: `DEFAULT`
- query param:
   `?filter=convenio`
- request:
```
{
   "filial": 101,   
   "perfil": 1,
   "convenios": [
       {
           "codigoConvenio": 416061,
           "matricula": "92052037004"
       }
   ],
   "itens": [
       {
           "codigo": 305103,
           "quantidade": 1      
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "precoDe": 64.66,
      "convenio": {
        "codigo": 416061,
        "filial": 1002,
        "descricaoAbreviada": "Bem Panvel",
        "percentualDesconto": 0.0,
        "associado": {
          "matricula": "92052037004",
          "codigo": 1539439
        }
      },
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.23 ean

- tipo: `DEFAULT`
- query param:
   `?filter=ean`
- request:
```
{   
  "filial":101, 
   "perfil": 1,   
   "itens": [
       {
           "codigo": 305103         
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "ean": 7795320008791,
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.24 possui-similares

- tipo: `DEFAULT`
- query param:
   `?filter=possui-similares`
- request:
```
{
 
   "perfil": 1,  
   "itens": [
       {
           "codigo": 2356           
       }
   ]  
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 2356,
      "codigoFilial": 101,
      "possuiSimilares": false
    }
  ],
  "packs": []
}
```

#### 2.1.25 bloqueados-internet

- tipo: `DEFAULT`
- query param:
   `?filter=bloqueados-internet`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "bloqueadoInternet": false
    }
  ],
  "packs": []
}
```

#### 2.1.26 descricao-detalhada

- tipo: `DEFAULT`
- query param:
   `?filter=descricao-detalhada`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103     
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "descricaoDetalhadaItem": "<p></p><ul><li><p>Conteúdo: 30 g</p></li><li><p>Uso tópico</p></li><li><p> regularmente por vários meses.</p><p><br></p><p></p>"
    }
  ],
  "packs": []
}
```

#### 2.1.27 venda-liberada

- tipo: `DEFAULT`
- query param:
   `?filter=venda-liberada`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 628430,
            "codigoFilial": 101,
            "vendaLiberada": true
        }
    ],
    "packs": []
}
```

#### 2.1.28 codigo-fabricante

- tipo: `DEFAULT`
- query param:
   `?filter=codigo-fabricante`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFabricante": 2442137,
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.29 tipo-item

- tipo: `DEFAULT`
- query param:
   `?filter=tipo-item`
- request:
```
{
   "filial": 101,
   "perfil": 1,   
   "itens": [
       {
           "codigo": 305103
        }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoTipoDoItem": 1,
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.30 nomenclatura

- tipo: `DEFAULT`
- query param:
   `?filter=nomenclatura`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "nomenclatura": "AZELAN CRE 30G                 P",
      "nomenclaturaDetalhada": "Azelan Creme 30g"
    }
  ],
  "packs": []
}
```

#### 2.1.31 psicotropico

- tipo: `DEFAULT`
- query param:
   `?filter=psicotropico`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "psicotropico": false
    }
  ],
  "packs": []
}
```

#### 2.1.32 retencao-receita

- tipo: `DEFAULT`
- query param:
   `?filter=retencao-receita`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
        }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "retencaoReceita": false
    }
  ],
  "packs": []
}
```

#### 2.1.33 otc

- tipo: `DEFAULT`
- query param:
   `?filter=otc`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "indicadorOtc": "S"
    }
  ],
  "packs": []
}
```

#### 2.1.34 custo-medio

- tipo: `DEFAULT`
- query param:
   `?filter=custo-medio`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]  
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "custoMedio": 44.64,
      "precoBaseZero": 45.43
    }
  ],
  "packs": []
}
```

#### 2.1.35 marca-pai

- tipo: `DEFAULT`
- query param:
   `?filter=marca-pai`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 153028
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "codigoFilial": 101,
      "codigoMarcaPai": 1966,
      "descricaoMarcaPai": "PYR-PAM                                 "
    }
  ],
  "packs": []
}
```

#### 2.1.36 uso-continuo

- tipo: `DEFAULT`
- query param:
   `?filter=uso-continuo`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "usoContinuo": false
    }
  ],
  "packs": []
}
```

#### 2.1.37 cupom-oferta

- tipo: `DEFAULT`
- query param:
   `?filter=cupom-oferta`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "codigoCupomOfertas":12164865,
    "itens": [
        {
            "codigo": 118716
            
        }
    ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 118716,
            "codigoFilial": 101,
            "codigoQuadroOferta": 2962,
            "cupomOferta": {
                "codigoQuadro": 2962,
                "codigoCampanha": 56,
                "percentualDesconto": 35.0,
                "codigoItem": 118716,
                "tipoCupom": "M"
            }
        }
    ],
    "packs": []
}
```

#### 2.1.38 situacao-item

- tipo: `DEFAULT`
- query param:
   `?filter=situacao-item`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "situacaoItem": "T"
    }
  ],
  "packs": []
}
```

#### 2.1.39 classe-terapeutica

- tipo: `DEFAULT`
- query param:
   `?filter=classe-terapeutica`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 35
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 35,
      "classeTerapeutica": "REPOSITOR DE VITAMINA D",
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.40 adesao

- tipo: `DEFAULT`
- query param:
   `?filter=adesao`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "permiteAdesao": false,
      "possuiKitAdesao": false
    }
  ],
  "packs": []
}
```

#### 2.1.41 exclusivo-panvel

- tipo: `DEFAULT`
- query param:
   `?filter=exclusivo-panvel`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "exclusivoPanvel": false
    }
  ],
  "packs": []
}
```

#### 2.1.42 item-geladeira

- tipo: `DEFAULT`
- query param:
   `?filter=item-geladeira`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 118464
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 118464,
      "codigoFilial": 101,
      "itemGeladeira": true
    }
  ],
  "packs": []
}
```

#### 2.1.43 participa-lista-referencial

- tipo: `DEFAULT`
- query param:
   `?filter=participa-lista-referencial`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo":  118556
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 118556,
      "codigoFilial": 101,
      "participaListaReferencial": false
    }
  ],
  "packs": []
}
```

#### 2.1.44 participa-farmacia-popular

- tipo: `DEFAULT`
- query param:
   `?filter=participa-farmacia-popular`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo":  519020
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 519020,
      "codigoFilial": 101,
      "participaFarmaciaPopular": true
    }
  ],
  "packs": []
}
```

#### 2.1.45 item-assinavel

- tipo: `DEFAULT`
- query param:
   `?filter=item-assinavel`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo":  305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "situacaoItem": "T",
      "itemAssinavel": true
    }
  ],
  "packs": []
}
```

#### 2.1.46 promocao-assinatura

- tipo: `DEFAULT`
- query param:
   `?filter=promocao-assinatura`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo":   153028
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 153028,
      "codigoFilial": 101,
      "promocaoAssinatura": false
    }
  ],
  "packs": []
}
```

#### 2.1.47 desconto-iav

- tipo: `DEFAULT`
- query param:
   `?filter=desconto-iav`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo":   14516,
           "codigoIav": 12241
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 14516,
      "codigoFilial": 101,
      "possuiItemAVencer": true,
      "iav": {
        "codigo": 12241,
        "precoDe": 12.84,
        "precoPor": 9.63,
        "percentualDesconto": 25.0
      }
    }
  ],
  "packs": []
}
```

#### 2.1.48 quantidade-apresentacao

- tipo: `DEFAULT`
- query param:
   `?filter=quantidade-apresentacao`
- request:
```
{  
   "filial": 101,
   "perfil": 1,
	 "itens": [
       {
           "codigo": 3506,
           "quantidade": 4         
       }
   ]
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 3506,
      "quantidade": 4,
      "qtdApresentacao": 120,
      "qtdApresentacaoUnitaria": 30,
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.49 participa-pbm

- tipo: `DEFAULT`
- query param:
   `?filter=participa-pbm`
- request:
```
{
   "filial": 101,
   "perfil": 1,
   "itens": [
       {
           "codigo": 305103
       }
   ]   
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 305103,
      "codigoFilial": 101,
      "participaPbm": false
    }
  ],
  "packs": []
}
```

#### 2.1.50 categoria

- tipo: `DEFAULT`
- query param:
   `?filter=categoria`
- request:
```
{
   "filial": 101,
   "perfil": 1,  
    "itens": [
       {
          "codigo":   14516
       }
			
   ]  
}
```
- response:
```
{
  "itens": [
    {
      "codigo": 14516,
      "categoria": "R",
      "codigoFilial": 101
    }
  ],
  "packs": []
}
```

#### 2.1.51 descontos

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=descontos`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "itens": [
        {
            "codigo":  494820
        }
    ],
    "consultaRegrasFiscais": {
        "uf": "RS",
        "pais": "BR",
        "ufDestino": "RS",
        "paisDestino": "BR"
    }
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 494820,
            "codigoFilial": 101,
            "descontos": [
                {
                    "origemDesconto": "CONVENIO",
                    "codigo": 412104,
                    "tipoDesconto": 3,
                    "percentualDesconto": 15.0,
                    "precoPor": 663.21,
                    "precoDe": 780.25,
                    "valorDesconto": 117.04,
                    "descricaoAbreviadaConvenio": "Convênio",
                    "aplicado": true
                },
                {
                    "origemDesconto": "PROMOCAO",
                    "codigo": 72803,
                    "tipoDesconto": 2,
                    "percentualDesconto": 4.0,
                    "precoPor": 17.11,
                    "precoDe": 17.82,
                    "valorDesconto": 0.71,
                    "precoUnitizado": {
                        "quantidadeComposicao": {
                            "quantidadeComposicao": 30,
                            "siglaUnidadeComposicao": "CO"
                        },
                        "precoUnidade": 0.57
                    },
                    "tipoPromocao": "Bem Panvel",
                    "dataInicial": "09/01/2018",
                    "aplicado": true
                }
            ]
        }        
    ],
    "packs": []
}
```

#### 2.1.52 preco-unitizavel

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=preco-unitizavel`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "convenios": [
        {
            "codigoConvenio": 416061,
            "matricula": "92052037004"
        }
    ],
    "itens": [
        {
            "codigo": 403014
        }
    ],
    "consultaRegrasFiscais": {
        "uf": "RS",
        "pais": "BR",
        "ufDestino": "RS",
        "paisDestino": "BR"
    }
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 3506,
            "codigoFilial": 101,
            "precoUnitizavel": {
                "quantidadeComposicao": {
                    "quantidadeComposicao": 30,
                    "siglaUnidadeComposicao": "CO"
                },
                "precoUnidade": 0.59
            }
        }
    ],
    "packs": []
}

```

#### 2.1.53 rentabilidade

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=advertencias`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "itens": [
        {
            "codigo": 305103
        }
    ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 305103,
            "codigoFilial": 101,
            "rentabilidadeReposicao": 16.62,
            "rankingItem": 17.0
        }
    ],
    "packs": []
}
```

#### 2.1.54 eans-alternativos

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=eans-alternativos`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "itens": [
        {
            "codigo": 878020
        }
    ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 878020,
            "codigoFilial": 101,
            "eansAlternativos": [
                7891268031706,
                7908236800124
            ]
        }
    ],
    "packs": []
}
```

#### 2.1.55 presenteavel

- tipo: `NÃO DEFAULT`
- query param:
   `?filter=presenteavel`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "itens": [
        {
            "codigo": 878020
        }
    ]
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 878020,
            "codigoFilial": 101,
            "presenteavel": false
        }
    ],
    "packs": []
}
```


#### 2.1.56 default (filtro para apresentar todos os tipo default, pode ser agregado com outros filtros não defaults)
- tipo: DEFAULT
- query param:
   `?filter=default`
- request:
```
{
    "filial": 101,
    "perfil": 1,
    "cep": 93010180,
    "convenios": [
        {
            "codigoConvenio": 416061,
            "matricula": "92052037004"
        }
    ],
    "itens": [
        {
            "codigo": 403014
        }
    ],
    "consultaRegrasFiscais": {
        "uf": "RS",
        "pais": "BR",
        "ufDestino": "RS",
        "paisDestino": "BR"
    }
}
```
- response:
```
{
    "itens": [
        {
            "codigo": 403014,
            "codigoFabricante": 2910941,
            "ean": 7896261004900,
            "precoDe": 107.15,
            "precoPor": 97.99,
            "quantidade": 1,
            "codigoPrincipioAtivo": 2137,
            "principioAtivo": "VALSARTAN/HIDROCLOROTIAZIDA",
            "classeTerapeutica": "ANTI-HIPERTENSIVOS",
            "promocao": {
                "codigoPromocao": 85782,
                "codigoFilialPromotora": 1002,
                "perfil": 1,
                "percentualDesconto": 8.55,
                "dataInicio": "02/02/2019",
                "dataFinal": "31/12/2020",
                "tipoPromocao": "Promoção",
                "descricaoPromocao": "CESTA BASICA DE MEDICAMENTOS RS 2019 (8,55%)",
                "codigoModalidade": 37,
                "descricaoModalidade": "CESTA BASICA DE MEDICAMENTOS"
            },
            "convenio": {
                "codigo": 416061,
                "filial": 1002,
                "descricaoAbreviada": "BEM PANVEL",
                "percentualDesconto": 0.0,
                "associado": {
                    "matricula": "92052037004",
                    "codigo": 1539439
                }
            },
            "origemDesconto": "PROMOCAO",
            "percentualDesconto": 8.55,
            "regraFiscal": {
                "codigoLegenda": 4,
                "codigoCfop": 5405,
                "codigoSituacaoTributaria": 60,
                "aliquotaIcms": 18,
                "mensagemFiscal": "CBM BC. ICMS E ST RED.P/ 38,8889% LIVRO I, ART.23,VIII E LIVRO III ART.106 DEC.37.699/97 E LEI 10278/94",
                "percentualIsencao": 8.55,
                "somaIsencaoComPromocao": false
            },
            "codigoTipoDoItem": 1,
            "categoria": "R",
            "codigoFilial": 101,
            "vendaLiberada": true,
            "descricaoDetalhadaItem": "<ul><li><p>Conteúdo: 28 comprimidos revestidos</p></li><li><p>Uso oral e adulto</p></li><li><p>Fabricante: Novartis Biociências SA</p></li></ul><p>Indicado para o tratamento da hipertensão arterial,<b> Diovan HCT</b> reduz a pressão arterial, sem afetar a frequência cardíaca.</p><p><b>Sua ação contribui com a saúde dos vasos sanguíneos do cérebro, coração e rins, evitando os problemas trazidos pela hipertensão, como o risco de ataques cardíacos, acidente vascular cerebral, insuficiência cardíaca ou insuficiência renal.</b></p><br><h2>Composição<br></h2><p>Cada comprimido revestido de Diovan HCT contém:</p><ul><li><p>160 mg de valsartana e 12,5 mg de hidroclorotiazida</p></li></ul><br><h2>Excipientes:</h2><p> </p><ul><li><p>Dióxido de Silício</p></li><li><p>Crospovidona</p></li><li><p>Hipromelose</p></li><li><p>Estearato de Magnésio</p></li><li><p>Celulose Microcristalina</p></li><li><p>Macrogol</p></li><li><p>Talco</p></li><li><p>Dióxido de Titânio</p></li><li><p>Óxido Férrico Vermelho</p></li></ul><p>A cápsula azul contém corante FD&amp;C azul número 2 laca de alumínio, a cápsula cinza contém<br>óxido férrico preto e ambas contêm dióxido de titânio.</p><p><br></p><h2>Para o que é indicado</h2><p>Diovan HCT é indicado para tratar a pressão arterial elevada, evitando o aumento de carga do coração e das artérias. </p><h2><br>Como funciona</h2><p>Diovan HCT contém um agente hipotensivo e um diurético que ajudam a controlar a pressão arterial elevada. A valsartana bloqueia o efeito da angiotensina II, uma substância natural do organismo que causa constrição dos vasos sanguíneos, aumentando a pressão arterial.</p><p>Como resultado, os vasos sanguíneos relaxam e a pressão sanguínea diminui. Já os diuréticos, ao aumentarem o fluxo de urina, ajudam a reduzir a quantidade de sal e água no organismo.</p><p>Na maioria dos pacientes, após a administração de uma dose única oral, o pico de redução da pressão arterial é atingido em 4 a 6 horas, persistindo por até 24 horas. Após 2 a 4 semanas, a redução máxima da pressão arterial com qualquer dose é geralmente atingida e se mantém durante a terapia em longo prazo. </p><br><h2>Para que serve</h2><p>Diovan HCT é ideal para os tratamentos de pressão alta, insuficiência cardíaca e pós-infarto do miocárdio em pacientes recebendo terapêutica usual.</p><p><br></p><h2>Contraindicação</h2><p>Diovan HCT é contraindicado para:</p><ul><li><p>Pacientes com reação alérgica ou incomum a valsartana, hidroclorotiazida, sulfonamidas ou a qualquer outro componente deste medicamento;</p></li><li><p>Pessoas com doença grave dos rins, não capazes de produzir urina (anúria);</p></li><li><p>Mulheres grávidas, com suspeita de gravidez ou em planejamento de engravidar;</p></li><li><p>Pacientes com alto nível de açúcar no sangue e com diabetes mellitus tipo 2 (também chamado de diabetes mellitus não dependente de insulina) enquanto está tomando alisquireno, um medicamento utilizado para diminuir a pressão arterial.</p></li></ul><h2><br>Como usar</h2><p>O medicamento deve ser administrado por via oral, com auxílio de água. Pode ser ingerido a qualquer hora do dia, acompanhado ou não de alimentos.</p>",
            "nomenclatura": "DIOVAN HCT 160/12,5MG 28 CP",
            "nomenclaturaDetalhada": "DIOVAN HCT 160/12,5MG 28 CP",
            "psicotropico": false,
            "retencaoReceita": false,
            "possuiGenericos": true,
            "lancamento": false,
            "possuiSimilares": true,
            "possuiAlternativos": true,
            "possuiSimilaresPorPrincipioAtivo": true,
            "possuiGenericosPorPrincipioAtivo": false,
            "possuiReferenciaPorPrincipioAtivo": true,
            "possuiItemAVencer": false,
            "bloqueadoInternet": false,
            "presenteavel": false,
            "situacaoItem": "T",
            "advertencias": [
                "A persistirem os sintomas, o médico deverá ser consultado."
            ],
            "farmaciaPopular": false,
            "multiAtendimento": false,
            "dadosImagens": [],
            "categorias": [
                {
                    "id": 1,
                    "descricao": "Medicamentos",
                    "nivel": 1
                },
                {
                    "id": 22,
                    "descricao": "Pressão Alta",
                    "nivel": 2
                },
                {
                    "id": 114,
                    "descricao": "Anti-Hipertensivos",
                    "nivel": 3
                }
            ],
            "linksVideo": [],
            "restricoes": [
                2
            ],
            "indicadorOtc": "N",
            "geraDadosFornecedor": false,
            "participaPbm": true,
            "permiteAdesao": true,
            "possuiKitAdesao": false,
            "exclusivoPanvel": false,
            "participaListaReferencial": true,
            "participaFarmaciaPopular": false,
            "participaPackNovo": false,
            "promocaoAssinatura": false,
            "itemGeladeira": false,
            "possuiEanImpresso": true,
            "usoContinuo": true,
            "codigoMarcaPai": 8301,
            "descricaoMarcaPai": "DIOVAN",
            "itemAssinavel": true,
            "custoMedio": 66.23,
            "precoBaseZero": 70.82,
            "reposicao": "Sim",
            "dataPrimeiraEntrada": "05/01/2006",
            "dataUltimaVenda": "27/02/2020",
            "dataUltTransRecebidaDimed": "22/02/2020"
        }
    ],
    "packs": []
}
```





### 3. Listagem de itens

Traz um pouco menos de informações como bula, advertências, itens alternativos e vídeos.

- POST http://localhost:9006/mostruario/v3/itens/lista

- Body
```
{
  "filial": 101,
  "cep": "string",
  "perfil": 2,
  "convenios": [
    {
      "codigoConvenio": 0,
      "matricula": "string",
      "codigoDependente": 0
    }
  ],
  "itens": [
    {
      "codigo": 27,
      "quantidade": 0,
      "isPack": false
    },
    {
      "codigo": 27,
      "quantidade": 0,
      "isPack": false
    }
  ],
  "codConvenio": 0,
  "consultaRegrasFiscais": {
    "uf": "RS",
    "pais": "BR",
    "ufDestino": "SP",
    "paisDestino": "BR"
  }
}
```

- Response
```
{
  "itens": [
    {
      "codigo": 27,
      "codigoFabricante": 45037,
      "ean": 7892828000019,
      "precoDe": 11.75,
      "precoPor": 10.58,
      "quantidade": 0,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "promocao": {
        "codigoPromocao": 81707,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 10
      },
      "origemDesconto": "PROMOCAO",
      "regraFiscal": {
        "codigoLegenda": 4,
        "codigoCfop": 6108,
        "codigoSituacaoTributaria": 0,
        "aliquotaIcms": 12,
        "percentualIsencao": 0,
        "somaIsencaoComPromocao": false
      },
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "descricaoDetalhadaItem": "<p>Este medicamento<span>&nbsp;&eacute; indicado para a preven&ccedil;&atilde;o e tratamento da car&ecirc;ncia das&nbsp;</span><span>vitaminas A, D e E</span><span>.</span></p>",
      "nomenclatura": "ADEFORTE 1AMPX3ML",
      "nomenclaturaDetalhada": "ADEFORTE 1AMPX3ML",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [
        {
          "sequenciaImagem": 29050,
          "numeroImagem": 1,
          "imagemPreferencial": "S"
        }
      ],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [
        2
      ],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": true
    },
    {
      "codigo": 27,
      "codigoFabricante": 45037,
      "ean": 7892828000019,
      "precoDe": 11.75,
      "precoPor": 10.58,
      "quantidade": 0,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "promocao": {
        "codigoPromocao": 81707,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 10
      },
      "origemDesconto": "PROMOCAO",
      "regraFiscal": {
        "codigoLegenda": 4,
        "codigoCfop": 6108,
        "codigoSituacaoTributaria": 0,
        "aliquotaIcms": 12,
        "percentualIsencao": 0,
        "somaIsencaoComPromocao": false
      },
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "descricaoDetalhadaItem": "<p>Este medicamento<span>&nbsp;&eacute; indicado para a preven&ccedil;&atilde;o e tratamento da car&ecirc;ncia das&nbsp;</span><span>vitaminas A, D e E</span><span>.</span></p>",
      "nomenclatura": "ADEFORTE 1AMPX3ML",
      "nomenclaturaDetalhada": "ADEFORTE 1AMPX3ML",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [
        {
          "sequenciaImagem": 29050,
          "numeroImagem": 1,
          "imagemPreferencial": "S"
        }
      ],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [
        2
      ],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": true
    }
  ],
  "packs": []
}
```

### 4. Detalhamento de informações de uma lista de itens

- GET http://localhost:9006/mostruario/v3/itens/precos?item=27&filial=101&perfil=2

- Response
```
[
  {
    "codigoItem": 27,
    "preco": {
      "precoVenda": 11.75,
      "precoPor": 10.58,
      "percentualDesconto": 10,
      "precoFidelidade": 11.75,
      "precoFidelidade55Mais": 11.75
    }
  }
]
```

### 5. Buscar itens alternativos a partir de um código do item

- GET http://localhost:9006/mostruario/v3/itens/400/alternativos?cep=91110001&filial=101&perfil=2

- Response
```
{
  "itens": [
    {
      "codigo": 419620,
      "codigoFabricante": 977652,
      "ean": 7896782806212,
      "precoDe": 19.16,
      "precoPor": 19.16,
      "quantidade": 1,
      "codigoPrincipioAtivo": 123,
      "principioAtivo": "CEFOTAXIMA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "G",
      "codigoFilial": 101,
      "vendaLiberada": false,
      "nomenclatura": "CEFOTAXIMA SOD 1G 1 AMP RANB GEN A",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NT",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 31109,
          "descricao": "Genéricos",
          "nivel": 2
        },
        {
          "id": 31111,
          "descricao": "Ampolas",
          "nivel": 3
        }
      ],
      "restricoes": [],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 3033,
      "descricaoMarcaPai": "FAMILIA GENERICOS",
      "itemAssinavel": false
    }
  ],
  "packs": []
}
```

### 6. Buscar itens genéricos a partir de um item

- GET http://localhost:9006/mostruario/v3/itens/779/genericos?cep=91110001&filial=101&perfil=2

- Response
```
{
  "itens": [
    {
      "codigo": 402532,
      "codigoFabricante": 924174,
      "ean": 7896112144755,
      "precoDe": 10.95,
      "precoPor": 10.95,
      "quantidade": 1,
      "codigoPrincipioAtivo": 223,
      "principioAtivo": "CLORIDRATO LINCOMICINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "G",
      "codigoFilial": 101,
      "vendaLiberada": false,
      "nomenclatura": "CLOR.LINCOMICINA 600MG 1X2ML TEUTGEN A",
      "nomenclaturaDetalhada": "CLORIDRATO LINCOMICINA 600MG 1X2ML TEUTO GENÉRICO",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "FS",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 31109,
          "descricao": "Genéricos",
          "nivel": 2
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 31110,
          "descricao": "Alergias e Infecções",
          "nivel": 3
        },
        {
          "id": 30,
          "descricao": "Antialérgicos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 3033,
      "descricaoMarcaPai": "FAMILIA GENERICOS",
      "itemAssinavel": false
    },
    {
      "codigo": 993810,
      "codigoFabricante": 4340282,
      "ean": 7896714202969,
      "precoDe": 9.87,
      "precoPor": 7.4,
      "quantidade": 1,
      "codigoPrincipioAtivo": 223,
      "principioAtivo": "CLORIDRATO LINCOMICINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "promocao": {
        "codigoPromocao": 75769,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 25
      },
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "G",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "nomenclatura": "CLOR.LINCOMICINA 600MG 1X2ML NEOQGEN A",
      "nomenclaturaDetalhada": "CLORIDRATO LINCOMICINA 600MG 1X2ML NEOQUÍMICA GENÉRICO",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 31109,
          "descricao": "Genéricos",
          "nivel": 2
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 31110,
          "descricao": "Alergias e Infecções",
          "nivel": 3
        },
        {
          "id": 30,
          "descricao": "Antialérgicos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 3033,
      "descricaoMarcaPai": "FAMILIA GENERICOS",
      "itemAssinavel": false
    }
  ],
  "packs": []
}
```

### 7. Buscar itens a partir de um princípio ativo

- GET http://localhost:9006/mostruario/v3/itens/27/principioativo?cep=91110001&filial=101&perfil=2&principioAtivo=4730&categoria=V

- Response
```
{
  "itens": [
    {
      "codigo": 345270,
      "codigoFabricante": 45037,
      "ean": 7892828000026,
      "precoDe": 64.09,
      "precoPor": 57.68,
      "quantidade": 1,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "promocao": {
        "codigoPromocao": 81707,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 10
      },
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "descricaoDetalhadaItem": "<p><strong>ADEFORTE GOTAS </strong></p>\n<p><strong>15ML</strong></p>\n<p>&nbsp;</p>\n<h2><span>Apresenta&ccedil;&otilde;es<strong></strong></span></h2>\n<p class=\"m_-1460673646320580640x_MsoNormal\">Frasco de vidro &acirc;mbar com conta-gotas contendo 15mL do produto.</p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span><br /><strong>Composi&ccedil;&atilde;o</strong><strong></strong></span></p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>Cada mL (20 gotas) cont&eacute;m: </span></p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>Vitamina A (sobre a forma de palmitato de retinol).......................................................... 20.000UI</span></p>\n<p class=\"m_-1460673646320580640x_MsoNormal\">Vitamina D (sobre a forma de colecalciferol).......................................................... 1.600UI</p>\n<p class=\"m_-1460673646320580640x_MsoNormal\">Vitamina E (sobre a forma de acetato de racealfatocoferol).......................................................... 30mg</p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>excipientes q.s.p. ................................................................................................... 1 mL</span></p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>(cremophor RH 40, bezoato de s&oacute;dio, &aacute;cido c&iacute;trico, fosfato de s&oacute;dio dib&aacute;sico butilidroxitolueno, &aacute;lcool et&iacute;lico, aroma identico ao natural de banana, ciclamato de s&oacute;dio,&nbsp; sacarina s&oacute;dica di-hidratada e &aacute;gua de osmose reversa).</span></p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>&nbsp;</span></p>\n<h2><span><br />Indica&ccedil;&otilde;es de uso<strong></strong></span></h2>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>Este medicamento &eacute; indicado como suplemento vitam&iacute;nico em dietas restritivas e inadequadas.</span></p>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>&nbsp;</span></p>\n<h2><span><br />Como funciona?<strong></strong></span></h2>\n<p class=\"m_-1460673646320580640x_MsoNormal\"><span>Duranto o tratamento com Adeforte, &eacute; esperado que a reposi&ccedil;&atilde;o das vitaminas A, D e E ajude a corrigir algumas doen&ccedil;as por car&ecirc;ncias destas vitaminas.&nbsp;</span><span>O tempo para o inicio de a&ccedil;&atilde;o do Adeforte, bem como a dura&ccedil;&atilde;o da a&ccedil;&atilde;o, v&atilde;o depender da necessidade org&acirc;nica de vitaminas de cada paciente.</span></p>",
      "nomenclatura": "ADEFORTE GOTAS 15ML",
      "nomenclaturaDetalhada": "ADEFORTE GOTAS 15ML",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [
        {
          "sequenciaImagem": 29109,
          "numeroImagem": 1,
          "imagemPreferencial": "S"
        }
      ],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [
        2
      ],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": true
    },
    {
      "codigo": 19830,
      "codigoFabricante": 45037,
      "ean": 7890282801166,
      "precoDe": 82.55,
      "precoPor": 82.55,
      "quantidade": 1,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "nomenclatura": "ADEFORTE MAIS 30CP",
      "nomenclaturaDetalhada": "ADEFORTE MAIS 30CP",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NT",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": false
    },
    {
      "codigo": 27,
      "codigoFabricante": 45037,
      "ean": 7892828000019,
      "precoDe": 11.75,
      "precoPor": 10.58,
      "quantidade": 1,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "promocao": {
        "codigoPromocao": 81707,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 10
      },
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "descricaoDetalhadaItem": "<p>Este medicamento<span>&nbsp;&eacute; indicado para a preven&ccedil;&atilde;o e tratamento da car&ecirc;ncia das&nbsp;</span><span>vitaminas A, D e E</span><span>.</span></p>",
      "nomenclatura": "ADEFORTE 1AMPX3ML",
      "nomenclaturaDetalhada": "ADEFORTE 1AMPX3ML",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [
        {
          "sequenciaImagem": 29050,
          "numeroImagem": 1,
          "imagemPreferencial": "S"
        }
      ],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [
        2
      ],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": true
    },
    {
      "codigo": 866200,
      "codigoFabricante": 45037,
      "ean": 7890282800176,
      "precoDe": 258.06,
      "precoPor": 258.06,
      "quantidade": 1,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": false,
      "nomenclatura": "ADEFORTE 25AMPX3ML",
      "nomenclaturaDetalhada": "ADEFORTE 25AMPX3ML",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NF",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": false
    },
    {
      "codigo": 651590,
      "codigoFabricante": 45037,
      "ean": 7892828001085,
      "precoDe": 43.55,
      "precoPor": 39.2,
      "quantidade": 1,
      "codigoPrincipioAtivo": 4730,
      "principioAtivo": "PALMITATO DE RETINOL/COLECALCIFEROL/ACETATO TOCOFEROL",
      "classeTerapeutica": "POLIVITAMINICOS",
      "promocao": {
        "codigoPromocao": 81707,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 10
      },
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "V",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "descricaoDetalhadaItem": "<p><strong>ADEFORTE </strong></p>\n<p><strong>60 Capsulas</strong></p>\n<p>&nbsp;</p>\n<h2>APRESENTA&Ccedil;&Atilde;O</h2>\n<p>C&aacute;psulas: suplemento vitaminico em embalagem contendo 60 unidades.</p>\n<p>VIA ORAL</p>\n<p>USO ADULTO E PEDI&Aacute;TRICO</p>\n<p>&nbsp;</p>\n<p><strong>COMPOSI&Ccedil;&Atilde;O&nbsp;</strong></p>\n<p>Cada mL (20 gotas) cont&eacute;m:</p>\n<p>palmitato de retinol ................................. 20.000 UI</p>\n<p>colecalciferol ............................................ 1.600 UI</p>\n<p>acetato de racealfatocoferol .......................... 30 mg</p>\n<p>Excipiente q.s.p. .............................................. 1 mL</p>\n<p>&nbsp;</p>\n<h2>PARA QUE ESTE MEDICAMENTO &Eacute; INDICADO?</h2>\n<p>Adeforte&reg; &eacute; utilizado na preven&ccedil;&atilde;o e tratamento dos estados de car&ecirc;ncia das vitaminas A, D e E, em crian&ccedil;as e adultos.</p>\n<h2><br /> COMO ESTE MEDICAMENTO FUNCIONA?</h2>\n<p>Espera-se que as doen&ccedil;as por car&ecirc;ncia de vitaminas A, D e E se corrijam &agrave; medida em que estas vitaminas s&atilde;o repostas. O tempo para in&iacute;cio de a&ccedil;&atilde;o, bem como de dura&ccedil;&atilde;o de a&ccedil;&atilde;o, depender&atilde;o da necessidade org&acirc;nica das vitaminas A, D e E.</p>",
      "nomenclatura": "ADEFORTE 60 CAPS",
      "nomenclaturaDetalhada": "ADEFORTE 60 CAPS",
      "psicotropico": false,
      "retencaoReceita": false,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [
        {
          "sequenciaImagem": 10612,
          "numeroImagem": 1,
          "imagemPreferencial": "S"
        }
      ],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 29,
          "descricao": "Visão",
          "nivel": 2
        },
        {
          "id": 24,
          "descricao": "Vitaminas e Minerais",
          "nivel": 3
        }
      ],
      "restricoes": [],
      "indicadorOtc": "S",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 37,
      "descricaoMarcaPai": "ADEFORTE                                ",
      "itemAssinavel": true
    }
  ],
  "packs": []
}
```

### 8. Buscar itens referência a partir de um código do item

- GET http://localhost:9006/mostruario/v3/itens/100710/referencia?cep=90110001&filial=101&perfil=2

- Response
```
{
  "itens": [
    {
      "codigo": 801060,
      "codigoFabricante": 2090204,
      "ean": 5702157150809,
      "precoDe": 257.55,
      "precoPor": 257.55,
      "quantidade": 1,
      "codigoPrincipioAtivo": 5001,
      "principioAtivo": "OXALATO ESCITALOPRAM",
      "classeTerapeutica": "ANTIDEPRESSIVOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "R",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "nomenclatura": "LEXAPRO 10MG 28 CP REV C1",
      "nomenclaturaDetalhada": "Lexapro 10mg 28 Comprimidos Revestidos C1",
      "psicotropico": true,
      "retencaoReceita": true,
      "possuiGenericos": true,
      "bloqueadoInternet": false,
      "situacaoItem": "FS",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 28,
          "descricao": "Sistema Nervoso",
          "nivel": 2
        },
        {
          "id": 143,
          "descricao": "Depressão",
          "nivel": 3
        }
      ],
      "restricoes": [
        2
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": true,
      "permiteAdesao": true,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": true,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": true,
      "codigoMarcaPai": 6626,
      "descricaoMarcaPai": "LEXAPRO",
      "itemAssinavel": false
    }
  ],
  "packs": []
}
```

### 9. Buscar itens similares a partir de um item

- GET http://localhost:9006/mostruario/v3/itens/92771/similares?cep=90110001&filial=101&perfil=2

- Response
```
{
  "itens": [
    {
      "codigo": 77852,
      "codigoFabricante": 7902713,
      "ean": 7896658001604,
      "precoDe": 19.71,
      "precoPor": 19.71,
      "quantidade": 1,
      "codigoPrincipioAtivo": 47,
      "principioAtivo": "AMOXICILINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "S",
      "codigoFilial": 101,
      "vendaLiberada": false,
      "nomenclatura": "NOVOCILIN 500MG C/15 CAPS",
      "nomenclaturaDetalhada": "NOVOCILIN 500MG C/15 CAPS",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NF",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 30,
          "descricao": "Antialérgicos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 1663,
      "descricaoMarcaPai": "NOVOCILIN                               ",
      "itemAssinavel": false
    },
    {
      "codigo": 202576,
      "codigoFabricante": 7902713,
      "ean": 7896658001635,
      "precoDe": 25.37,
      "precoPor": 23.85,
      "quantidade": 1,
      "codigoPrincipioAtivo": 47,
      "principioAtivo": "AMOXICILINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "promocao": {
        "codigoPromocao": 75769,
        "codigoFilialPromotora": 1002,
        "perfil": 2,
        "percentualDesconto": 6
      },
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "S",
      "codigoFilial": 101,
      "vendaLiberada": false,
      "nomenclatura": "NOVOCILIN 500MG 21 CAP",
      "nomenclaturaDetalhada": "NOVOCILIN 500MG 21 CAP",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": false,
      "situacaoItem": "T",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 32,
          "descricao": "Antibióticos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 1663,
      "descricaoMarcaPai": "NOVOCILIN                               ",
      "itemAssinavel": false
    },
    {
      "codigo": 925140,
      "codigoFabricante": 10226319,
      "ean": 7897595600912,
      "precoDe": 19.45,
      "precoPor": 19.45,
      "quantidade": 1,
      "codigoPrincipioAtivo": 47,
      "principioAtivo": "AMOXICILINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "S",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "nomenclatura": "AMOXINA 500MG 8 CAP",
      "nomenclaturaDetalhada": "AMOXINA 500MG 8 CAP",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NT",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 32,
          "descricao": "Antibióticos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 8779,
      "descricaoMarcaPai": "AMOXINA",
      "itemAssinavel": false
    },
    {
      "codigo": 925150,
      "codigoFabricante": 10226319,
      "ean": 7897595601636,
      "precoDe": 22.99,
      "precoPor": 22.99,
      "quantidade": 1,
      "codigoPrincipioAtivo": 47,
      "principioAtivo": "AMOXICILINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "S",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "nomenclatura": "AMOXINA 500MG 12 CAP",
      "nomenclaturaDetalhada": "AMOXINA 500MG 12 CAP",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NT",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 32,
          "descricao": "Antibióticos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 8779,
      "descricaoMarcaPai": "AMOXINA",
      "itemAssinavel": false
    },
    {
      "codigo": 925160,
      "codigoFabricante": 10226319,
      "ean": 7897595601629,
      "precoDe": 31.85,
      "precoPor": 31.85,
      "quantidade": 1,
      "codigoPrincipioAtivo": 47,
      "principioAtivo": "AMOXICILINA",
      "classeTerapeutica": "ANTIBIOTICOS",
      "origemDesconto": "PROMOCAO",
      "codigoTipoDoItem": 1,
      "categoria": "S",
      "codigoFilial": 101,
      "vendaLiberada": true,
      "nomenclatura": "AMOXINA 500MG 21 CAP",
      "nomenclaturaDetalhada": "AMOXINA 500MG 21 CAPSULA",
      "psicotropico": false,
      "retencaoReceita": true,
      "possuiGenericos": false,
      "bloqueadoInternet": true,
      "situacaoItem": "NT",
      "farmaciaPopular": false,
      "multiAtendimento": false,
      "dadosImagens": [],
      "categorias": [
        {
          "id": 1,
          "descricao": "Medicamentos",
          "nivel": 1
        },
        {
          "id": 11,
          "descricao": "Alergias e Infecções",
          "nivel": 2
        },
        {
          "id": 32,
          "descricao": "Antibióticos",
          "nivel": 3
        }
      ],
      "restricoes": [
        4
      ],
      "indicadorOtc": "N",
      "geraDadosFornecedor": false,
      "participaPbm": false,
      "permiteAdesao": false,
      "possuiKitAdesao": false,
      "exclusivoPanvel": false,
      "participaListaReferencial": false,
      "participaFarmaciaPopular": false,
      "participaPack": false,
      "promocaoAssinatura": false,
      "itemGeladeira": false,
      "usoContinuo": false,
      "codigoMarcaPai": 8779,
      "descricaoMarcaPai": "AMOXINA",
      "itemAssinavel": false
    }
  ],
  "packs": []
}
```
