# Classes de Cast

Estamos jogando em um mundo que a magia ela não flui ela ALAGA as coisas.
Com isso alem de varios itens q viram ao longo do jogo vão beneficiar as classes não magas as classes magas não precisam mais preparar magias.

Como isso vai funcionar? Vamos usar o Clerigo como exemplos:

O Clerigo no lvl 3 tem 4 magias de 1º nivel e 2 magias de 2º nivel, logo ele tem 6 slots de magia.

Vamos supor que ele rodou muito bem os dados então ele tem uma pool de mana de 21 de mana [veja como calcular mana aqui](./spell-cast.md).
Por ser lvl 3 ele ***AINDA ESTA LIMITADO*** as magias de 1º e 2º nivel.

Como ele não prepara mais magias e usamos mana em vez de sloot ele tem acesso a castar TODAS as magias dos leveis liberados enquanto ele tiver mana.
Contudo existe limitação, vamos pensar como uma tabela, ele teria 4 slots 1 e 2 slots 2 logo 6 slots total.

Cada magia q ele casta ocupa um slote livre do seu "grimorio mental".

| SLOT| SLOT| SLOT| SLOT|SlOT| SLOT|
|--|-|-|-|-|-|
|  |  |  |  |  |  |

Esses slots são "limpos" em um descanso longo assim como a mana volta ao descanso longo.

Durante o jogo ele decide castar uma magia de lvl 2 (A2)

| SLOT     | SLOT| SLOT| SLOT|SlOT| SLOT|
|----------|-|-|-|-|-|
| Magia A2 |  |  |  |  |  |

Para esse cast ele simplesmente casta normalmente e gasta a mana de acordo com a tabela q nesse exemplo seria 4.

O Clerigo tem 21 de mana e gastou 4, logo ele tem 17 de mana.

Durante o jogo ele casta mais 4 magias de lvl 1 totalizando 12 de mana gasta ficando com 5 de mana.

| SLOT     | SLOT | SLOT | SLOT | SlOT | SLOT|
|----------|------|------|------|------|-|
| A2 | A1   | B1   | C1   | D1   |  |

Ele consome um pot de mana e volta a ter 10 de mana e casta mais uma magia de lvl 2 porem diferente.

| SLOT     | SLOT | SLOT | SLOT | SlOT | SLOT |
|----------|------|------|------|------|------|
| A2 | A1   | B1   | C1   | D1   | B2   |

O Clerigo tem 10 de mana e gastou 4, logo ele tem 6 de mana.

Agora ele pode:
* Castar qq uma das magias sendo elas A1, B1, C1, D1, A2 ou B2 apenas pagando mana.
* Castar qq magia q não das ja castas no dia POREM alem da mana ele tem q passar em um teste de CD para tentar fazer isso

Esse teste sera CD 10 + 1/2 do lvl de cast (arredondado pra cima) + lvl da magia + vezes acima dos slotes

Assim se for magia de lvl 1 seria CD 10 + 2 + 1 + 1 = 13 

Julgando q ele ainda tenha mana pra isso e caste agora uma de lvl 2 seria CD 10 + 2 + 2 + 2 = 16

Assim sucessivamente ate ele esgotar sua mana. Vale lembrar que interpretação conta muito e o mestre pode dar vantagem ou desvantagem dependendo do que o jogador quer fazer.

Falhas criticas podem "fechar a mente" do personagem e ele não conseguir mais castar magias por um tempo ou ate mesmo perder a magia entao uso com sabedoria.