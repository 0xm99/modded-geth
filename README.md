# Zdarfa (Moppy) Custom Modded BSC Geth

>Advanced modified geth  for your Private Node.
>
>Sniping speed on Txpool (mempool) is drastically increased ! 

## Public tests:
>Modded geth VS default geth tests: 6 servers, each one with a dedicated full BSC node and a basic nodejs sniper on it.
>
>1 server = 1 node = 1 sniper. Same servers location, same settings for everyone.
>
>We sniped 20 times "addliquidity" on Cake with the 6 snipers at the same time.
>
>### ►► RESULT: Modded geth (SERVER A)  won 16 snipes out of 20 ◄◄

##
## Details:
__ 

**_Liquidity provider is using default public node_**

►Liquidity provider : <https://bscscan.com/address/0x83dc5e823f608935dcf57f5b3317e4fba4a878fd>

__ 

**_All the snipers are using localhost ws endpoint:_**

►Sniper on server A (modded geth) : <https://bscscan.com/address/0x8042A6849A5d83771a6408E3eC175A0D8599203a>

►Sniper on server B : <https://bscscan.com/address/0xb005880498fd27ef19eebd7459827b9317b2f5d6>

►Sniper on server C : <https://bscscan.com/address/0x400CE587f1761AD17ac486b73D5dF855247C840B>

►Sniper on server D : <https://bscscan.com/address/0xdfe23a9cd81191911148ca5180fefcc920b9b2f7>

►Sniper on server E : <https://bscscan.com/address/0x500d2e2e35c8fd13aa27e91a72dbf9c46592883c>

►Sniper on server F : <https://bscscan.com/address/0x1a55b71843a44fdb5e39fc6f26be3e79d8394c6d>

__


►Result of the node race :

```

NODES                  	A (mod)	B	C	D	E	F			A Rank(modded geth)	

position on block	23	35	57	37	36	40			1
position on block	67	82	70	72	69	74			1
position on block	52	65	59	54	63	53			1
position on block	39	54	40	41	37	47			2
position on block	54	65	55	57	56	71			1
position on block	119	134	129	120	132	130			1
position on block	30	48	31	36	37	58			1
position on block	68	86	70	71	74	76			1
position on block	112	127	120	113	124	132			1
position on block	77	61 +1*	79	80	78	63+1*			1
position on block	128	146	145	130	129	12+1*			1
position on block	51	62	54	52	38	39			3
position on block	21	56	35	27	38	23			1
position on block	179	194	193	182	180	181			1
position on block	90	102	94	93	91	92			1
position on block	194	201	195	193	187	192			3
position on block	36	51	39	38	37	52			1
position on block	33	44	36	32	34	51			2
position on block	86	109	88	91	87	114			1
position on block	11	19	15+1*	12	16	15			1

								TOTAL WIN MODDED GETH: 16/20


*+1 means 1 block late

```

## Contact ##

<https://moppynodes.com>

<https://t.me/bscprivatefullnode>

<https://t.me/zdarfa>



