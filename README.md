Verkefni unnið í RAF620M Inngangur að vélrænu námi og gervigreind við Háskóla Íslands.

# Úrdráttur

Í þessu verkefni var reynt að spá fyrir um fjölda koma á Bráðamóttökuna í Fossvogi út frá veði, 
degi árs og hvort það var helgi, frídagur eða stór hátíð. Sett voru upp tvö líkön, eitt línulegt 
aðhvarfsgreiningarlíkan (e. *linear regression*) og eitt flóknara, LSTM-líkan, 
(e. *long short-term memory*). Niðurstöður líkananna voru síðan  bornar saman við 
hvor aðra og einfaldar ágiskanir út frá meðaltali koma og hlaupandi meðaltali. Kom í ljós 
að hægt var að spá fyrir um fjölda koma með meðaltalsnákvæmni, (MAE), upp á 12,9 manns á dag 
ef stuðst var við flóknara endurtæka (e. *recurrent*) LSTM-líkanið. Aðeins lakari niðurstöður 
fengust með aðhvarfsgreiningarlíkaninu þó svo að meðaltalsnákvæmnin (MAE) væri aðeins lægri þar sem 
MSE-gildið hjá LSTM var betra. Bæði líkönin skiluðu betri niðurstöðu en einföldu ágiskanirnar og gáfu 
niðurstöður verkefnisins vísbendingar um að gera megi enn þá betra líkan til þess að spá fyrir um komur á Bráðamóttökuna.

# Höfundar
- S. Maggi Snorrason
- Ólafur Heiðar Jónsson
