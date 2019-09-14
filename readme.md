
# <center>Anotações Unity2D</center>

#### Sumário:

 1. [Geral](#Geral)
	* 1.1 [Awake e FixedUpdate](#Awake-e-FixedUpdate)
	* 1.2 [Propriedade Transform](#Propriedade-Transform)
	* 1.3 [Projeções](#Projeções)
	* 1.4 [Layers](#Layers)
 2. [Movimento](#Movimento)

[========]




## <center>Geral</center>
## **Awake e FixedUpdate:**
**Awake** é inicializado antes de **Start()**.
**Update** é chamado apenas uma vez durante a execução, e **FixedUpdate** é chamado varias vezes durante a execução, sendo assim essencial para atualização da posição e movimento.
## Propriedade Transform:
A propriedade Transform é responsável pela **Posição**, **Rotação** e **Escala** dos objetos.

## Projeções:
As projeções podem ser **Ortograph** ou **Perspective**.
**Ortograph** possui as propriedades X e Y.
**Perspective** possui as propriedades X,Y e Z.

## Layers:
Escrever sobre os layers depois

## <center>Movimento</center>
- Adicionar propriedade **Rigidbody2D** ao elemento que vai ser movimentado.
- Após isso para que o objeto não caia da tela, alteramos a propriedade **GravityScale** para 0.
