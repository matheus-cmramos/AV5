# AV5
Exercício: Considere uma cadeia circular composta por  átomos, cada um de massa , conectados por molas idênticas de constante elástica . O sistema está sujeito a condições de contorno ou seja a primeira massa está ligada a última massa. Em uma das simulações, introduza um defeito de massa:  substitua uma massa m2 (m2=5m)
 
## Parâmetros:
- Massas padrão:  m=1 kg
- Constante elástica: k = 1 N/m
- Tamanhos da cadeia: N = 100, 1000 e 10.000
- Defeito: massa igual a m2 = 5kg  (apenas em uma das simulações)

## DOS's:
-> Na cadeia homogênea: 
- A DOS (histograma das frequências naturais) se aproxima de uma função tipo parábola invertida à medida que N aumenta.
- Para N pequeno (ex: 100), os níveis são discretos e espaçados.
- Para N grande (ex: 1000 ou 10000), os níveis se tornam quase contínuos, formando uma distribuição densa e suave.
- Isso é esperado do limite termodinâmico (muito N), em que a cadeia se comporta como um meio contínuo.

-> Na cadeia com defeito: 
-Aparece uma frequência isolada, fora da banda contínua (normalmente abaixo da banda, se o defeito for uma massa menor).
- Esse modo localizado não se mistura com os demais — ele é um sinal direto do defeito quebrando a simetria translacional da cadeia.
- A DOS mostra isso com um pico isolado ou deslocado da distribuição parabólica principal.

## Modos normais:
-> Na cadeia homogênea: 
- Modos são ondas estacionárias, com simetria clara e nós/ventres bem definidos.
- Modo fundamental → deslocamento global suave.
- Modos superiores → mais nós, maior frequência, maior curvatura.

-> Na cadeia com defeito:
- Os modos de baixa frequência ainda lembram ondas suaves.
- Modos intermediários e altos são distorcidos localmente.
- Um ou mais modos passam a ter um padrão de deslocamento concentrado em torno do defeito → isso indica localização do modo.

## Localização dos modos associados ao defeito: 
- Quanto maior o N, o modo localizado pode ficar "escondido".
- Como a massa defeituosa é maior que as demais, o modo localizado terá frequência acima do limite superior da banda.
