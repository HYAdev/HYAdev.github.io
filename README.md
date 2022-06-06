## Question:
> The local Konica Minolta printer overheated. Can you find out why?
> [corrupt.lava](https://ctf.n00bzunit3d.xyz/attachments/Hot_Stuff/corrupt.lava)

## Solution:
> We are given *corrupt.lava*. The file by itself cannot be opened, due to its file type of lava. Let's see what happens if we change the file to a known file type, such as *.txt*?

```
%-12345X@PJL JOB NAME="wrap in 'n00bz{}'"
%-12345X@PJL JOB USERNAME="0xBlue"
%-12345X@PJL JOB TIMESTAMP="05/31/2022"
%-12345X@PJL JOB OSINFO="Blue0S"
%-12345X@PJL ENTER LANGUAGE=LAVAFLOW

E&l0S&l0G&u146D&l154X&x157X&l0O*r157U*g162W∞X�*b151M&l1A&l3H&l1M&l163E*r154S*r141T&l0U&l0Z*p166X*p141Y*r1A*b20V�����P��l���Ä��\*b3W·˝lﬁ6Òäq%HÅÍ|6�ãƒŸ†Ë-∆Ã@ñ8„é8„é8„é8„é8„é8„é8„é8„é8„é8„é8„é8–Õøê����Ê8Ä���^~�ZëÅP«¶ Á®–,ºÂF%çãàqIoÙ≤2	‘;Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæ˚Ôæı@��%@@��ö¡Ó$öo“§ñ·/Gxæ‘8aã|„ﬁíæJ§íI$íI$íI$íI$íI$íI$íI$íI$íI$íI$ëlp��.!��\ò.+r~ô‰¨≈""Ï~€¢öE6 ¡àzõEQEQEQEQEQEQEQEQEQEñ$kâ��‡4¶
'ÜÓdæf‰ﬁH∫èKc.\ õìméıj¶€ï"ı|»ä°R©Ñ∏†∆@IŸÖ ¸™Ù
ÆLúQEQEQEQEQEQEQEQEQEQE¢˛L´Iùb›ìFB1Ä�|MÅwñ÷úq0BôgYhÒîâç∏0÷7ÜÒõ\áàÅjê‰˝îœ%iòÿ˘§È»w¡W;cÿ'O7àØO˛÷‰AAAAAAAAAA˙ìœ—∏¬ƒÜÑè◊éáÓı<ô–±@Uå¶ˇ�'“ò∏b•¯Ùï∑Ωh¬qŒá>⁄V÷ó'éƒ˜h^bæ„Ó…‘Ôgr©¡Pﬁ:µJü’o∂cí˜“K˙ø_èÇ—ﬁeŒÓıE/‰—Í¨[†Ú¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶öi	ÊIé¡9ŒDæòç"1èQMöÙF6ÀÔ§?FÊ4∂}2‰·ö⁄¶“ÌïD8k;u∑çø.í®Cá Ú3‹»‚h˙‘ìh™ÒÚu„bÙ≤âXo#~∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫Î≠q”iï!@C¯çÆÂGB~ ñ»î∆™L,ˇw˝Ÿ:»äÉ�.—Ñµ„‰ÎÕºÁÙhÛÌ‰o◊]u◊]u◊]u◊]u◊]u◊]u◊]u◊]u◊]u◊]u◊Z†ÕÌ√¥��rÖ-i=È|©H¨Òu¥ÖÑ)†ò°ı	ÚÖÚ°Ãl7˙~∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ∫ÎÆ¥Òï¯≠`AuÅ[$��ÉÜ‰ﬂ%˝d#á·÷wÓ“ÃÎ©ºÆ§ùÍ£xN3≈?A @Å @Å @Å @Å @Å @ÄË›K¸\áß?l1©áä÷:¨TûÄ	ÿ˝c1èÊ("2Ïàíf—å:ú≥¢ıKM&”«ö2Û]©=Û{ù⁄◊5¡ü’€Q»¬ÖÙ*p”üÇocƒœ¨ımì—EQEQEQD˙ãœ˜l$€m∂€m∂€m∂€mÌ0o£”jüQÆb*¿˚’r¸/�bÁøø·"h˛»§ÇÂØ∏n8X˛i2#ÛÎ’Ùç(a`�Lvsb"˝`mqÕnÊº:È]o[∞Àõó{„)õ8As«ıµD"õìØ^ΩzıÎ◊Ø^ΩzıÎ◊Ø^ΩzıÎª*é1]ƒÉd˚Ôæ˚Ôæ˚Ûs)ˆ""=É©'†løB}g1˛Ù‚œí€e™Ã1∂_[å‚Y˜·Ëÿä´%ƒvrÚ∂fΩcçÜıÎ@≠öÊ
\SèñàDèƒÍ§)éU£U†`[X∑"PŸéÏpdn›FaΩ]˙Ê`Å @Å @Å`'f∫qqqqqqqqqqqqqqqqqq=O≈ªãôN˛/òT∏[{RŸÇè«˘(ÛÄ8¶`∑÷XÕkô7∏f%óì∞™_®ÁË`F°+wG‘ƒIQñG`±ÌÌÙ¨ÓLÚAè EF(q¯ä·H≥r|ãmÏ^‚Æ˘�◊›.ƒt≥7ö®ë2l58Ja5j’´V≠Zµj’´V≠Zµj’´Uú—Ò�•≠U´Æ∫Â∑X~Ωè!∆
òSƒ≠ﬂŸ vú¸n=åW/@¯˘÷π�x3Kˇ�~�Qw)Bd…P‰u.–√˝EÇ·O?ë√'qüÅ¿„≥ˆ”Éœm$∏|≈˚E•KŒç^{≤[rl√;§ÜW´Òs‰ﬁÿëÄÊÇ)ö˙%iG˛/›ËjàïwÔﬂø~˝˚˜Ôﬂø~˝˚˜Ôﬂø~≠¢«òv›=m#
%ßbfêú{t€È]mü^ªÏÆî†Pq/
–�hsq9”Ù…cu≈¯ö‹7Ê@udÎô∑9]9¶kìÜ°„]èF%-8´GL¥R>[/˜g-¸‘}Ûˇ�Üø≠˜j%ß	{Nˇ
ÖKªvÂØ2Ú
M£g1<n†`tÆ€hÓ.<xÒ„«ä∑J?.8„é0G)ûô}]up¢â“ól4MâQ…è!Ω�å‘gÍoÓ˝Kˇ�Ç|�"¬z≥∑hd≠†v”OKËäãà¯≠•§Îî6òIµå
§ø· 'nuH≈K◊¿¨–Xö·ù¸í.x+Ì
Ω\÷˜–nHá'£	:÷üJœ6
p‡Åàœ<Ûœ<Û» Åó√‚ú“Ú�ãÀ1»ìﬂlá�àå <ß[&+_¢VπTÍ∆ífq.(H˚˙=á‘˘,’Îµ√Ém>éúê[ÃA∆∑hmÛŸñ7—˜’§æûÃú¥¸¡∫[p·√á8pﬁhïQù5à3ﬂÀ£ääN˘˛¿t
Û8tl9nÌÖW@3OﬂZòép$§ÆœI~ñÔb∆àÉÂ„¿É ©Ò>Äân°/«p◊Ø¸-?ß{ ≈:πä9ÓO^∏c`u@mÊŸB®”˘ËZ(r—™àaÜaÜaÜaÜaÜa|´∂®˚<Û∫DÌﬁ^¶Iœù°◊
æ/^qb‘¬òÍe§\ä√æy„˝Í≥>Hs≥h‘cÙˆ˝≥∂7ÊâOy¯8B"âœıÜWÀÈ¸Ó˚–yıhÈFM|ÁEñˇ�Fºÿ,\ÃkÇ"ø£p7Ã´H#´¨ıiÓ6ÊÏ4M`ã…Û23£ÔïBN¯dø3aÜaÜaÜaÜaÜaC†0√“i∫oˇ�ˇ�ÙÇç‡1¥˘ÆÍ¥ﬂ∫ˇ�ºäDJ∂3pﬁM>cm
»Ï¿ù™gvõooÜyÑ§Oº‚¥ãÀÁ�;ü HÍÇÆ6;¬ù_+OËıûïyÌZn©P;ÙÊ¯åÒ^∏&ÑO!€ß”£™]M.ó˝æ!èÅ’‘Á;
5πKWÑì�2ëí6≥#õAss:√'WKõô#ù˛@fk#B\™<‰JırÈ\@k´z‘—r'Ôæ˚Ôæ˚Ôæ˚Ôæ˚◊Ó3ËÙƒ≠∫Î•¯tùøÀ‡8±ÌÃüé®3;~´àìB’∆Lˆç3!	9@JH˜¢Ü'dláÅ¸⁄ä;ê¨¬ò^¿}G°X&lïoÊêæ¯eØGœËu´F2-	fUG¸¿0ùº2jÈN?(_æ∏µågÉYK»°ñO˚N∆˚%WD=ˇ�	G:`cKâŸÄ¨◊ˇ�ß¡¬Ò}≥	@Èsˇ�ÌÃ0√0√0√0√0≤AAÛ∞ù›÷nõÀCG¯+`I<b¥Ç1
okùÃ3Å2⁄bwu∫√µÃùDGm4Àb™ƒÃwÕ»~ÿ∏+óÃªÃÈÈ√êR@»ﬁ⁄˘
±ä◊0{1+D]ì»π¨6 	u+6GAeÓØ‰bî!6ZêÃíeéSµõ†∏:≈å≥ã∆ñ¸üÉ√ABbÄôØ∆Úv&9mŒûUÇc€î$ê$Ö•G÷Ô8@ãn∫Î¶@LêÄWÏ9gŒ¶∆;“áa˙±Œ∞ﬂ±z°+a‚:´NÁµR¨ËÅ«ÿÇ<õ5Yõ¸ìpÌ|UÃ¢lã˚ÚñK”V‘«K¥|,}�…û¯<:¢”BØ§C7bE€§GÜEñà@nﬁ≥;FSùüœyëd⁄7^CË`ãl÷YÚÅ	Sde¥Iê¿@ˇµS∂CJZIIœÛ”¬>àã@ÄëÚ3Q‹æoØ…5Aè«•bî®ür·&’À 2>^≥Á√c∫´‘vı7√≈V;6lŸ≥dW©—(£ß
î{gB•DÅË©Æï<•Úª
yÌR)$ü$–O(•À$_ñg/Èú∏AD¬ı n±Ø©;¿ƒ8˝g~7%5rÚ‚Ç1çŒ'`ÊH“7Xõı´N™°˛ÿ‡}Ö*ÙºÄ>(‰yÜ°ÈL†ﬂ©ú““°h˛¯qb∂BoÇf≠„ı7?¨/§ê∑æ˘ŸÑ']G3™3y»©ñ˝¢†Z†Œû(™ÿßk‚„JSŒgîÎ•O8:G"ﬁÜˇ�õ:ﬁ
£oç≤üÉÈŒÌq—sïùª9r¸∏aÜ{–Oê<˙GÇ6µ'qÑü≠“#zzwÁkë∫!*CpïqO∞Ì$Qˇ�h3È�ÖZ’f{Ni…ºñ2&ÀúÉÏa©©ÖXii¬vï≥ÎÕkwîdÒ£∑iQMpYø?<∑ü≠Ïx_gˇ�Ñ‡4˚ÒÑI˛BÈ∫}î	] Xï´9∫HYb4Ø~9ë‹zˇ�¶“ŸHä9 „ôW‘qÍ∆Eñˆx0ImWˆ<1&ﬁ†/ˆ|˝˜S&®]˙Q¢˝%≠Ênwö®ç{~Ëœ^ªl–L1ôPZ{Mµ®≤énÏ˝x?gû83gzì\-—D£Uø˜i∂˚pÀŸhw"†ﬁ•˛a\ñYeñYeñW≤ªJ’–LvS§±Ë˚Ê}¿+,>Ëæx`KHb´Èh ,ıüÒz¡Sï”a‡ùÓº‘ª¨{l[8€$±T®t»ˆü]
ÕËI«∏FÓF¬À„-7èï∏º≤í,z–iJFWˇ�îãoä`wÄ}÷y›¯´tV¨ÌÖ\Ö¯gÕÑÉ
çÓNﬂ_U@î¨uSœ\∏Ç4jÖl•Jª)Â8g¥¥”“¿⁄*ú¸ìeﬂÂ≠øÍªé›ÿ´	Ft+5ne;Ôæ˚!µ˜ûÅDF«bÏæpÒogì(	[éır8/˝“w)⁄»/-KÍ∑g2&©?>Gı∆fÓÈñÖ
1JÆ≥ãπÛåÅí¡±‹Â‡#åG¬á±c´È“œ9ï⁄-›0ırñ¿Êàì°˘†ÓDé,E‚Åó≈‚-à9å=ı‡hG©Ï˝âõ6∑†égyL‡ïSïÀùˆ~L–ïA–L}™X˙†∞®
`P!7¨w^æ $Dº9~Æπ
_Ê3◊L4T\E{¬¿èÕrw∑§9ÿ*≤äy–¿¸[à·¸˘_¢tø*ˇ�Ò—ÇàŒ#2•_WèﬁyÁûyÁûk,”p^å∏îÕ‚H.Ω…4è%K¬ËÒ£‰ÕãŸ=Ñ+•Öí"¯êÿ4—uÎ]UûT,ê*;˚;ï[ IW‚ß/#‚EbÙ/=›ÑµN∂2øh§EA˚üàÇ6Õh!QûeWªEÇb∑˜ıËeÕø=◊˚πË W‡W≤¯/a6∑í|¯sFdfX’ÛeoG¢cR¨ÃåèÔÚˆ£ˇ�6wá®]j.Eähb$«ÎNÙÙÙ¯›¥∑,B™#Èı0º{cäÕÊæ>˛;:ô”îÇU@¯‘,¢∞ŸV}ñ	á}Yu£√«Óó~ï9Â¨dËpäe~pMM~|ƒj4√&Én∆!ÍòVv˛ÉX
pò¢zø≠ÓeöN@=‚◊§öΩÙI$íI$íI"Fi„⁄´Ω.C=Ôâ±ùf´ˇ�"óÃè_I˜∑9†$ŒÒ'ãˆÍ-ÕÄ∆·uRÀï≤ÿŸd—Ëd`ótÛô´ÿC—†¯uH®4I˜qÛŒ/„ejrü8}¶ràÜn[ëj£ózù:	÷—«p‹TË…zï]∫#XÃ∂Éb1u5‹ö?"XW€qVN�ÄÅG¸¥Ω‹…Õ`S¨r€§…á¬µ±Û9e≤m&¨éü√™%O)
<¯œâ0s%¥≥§r5�©ØÖ≈aíÂ∫;u›oB()Vñ†ù™ˆ∂ﬁÒY?†à‘ª´-� Uõªt'Ô*{Ç«vBt”F∞_\öÉü@
πMÓÕ˙Œœÿ~∂!	ÙJ∫QÄ#Áí@ÌÆ∫ÎÆ∫ÎÆ∫ÛÅ]\Ÿö¥à}Ç42Ë®ÓÑPiÂõ:–ﬁ∞Ó€©¥îRHØÆ\ê‘‚6.5¢)…Ne°)¸©ä«K@ÎÑøÍuD—$êK,h,Æ&∫8˘tÉY±Æ«É√≤â‹q î)8ÜU‰ã·È2»«”Á5›:´œÍ»„ã6279`úœJ√íÏ.≈ˆ˜§T€,[(ªRe∏Ñ{4‘~‹≈)j◊g	+‘s¥%ÚuWÿÃ‰ÉòMÂt€¶ôød¬±dóê�Ç Ç ÇH’çΩïûùU@PXb∞9(˙Â#ñãXw
Ä{`5∆A p∂Å≈Ap~˙¨xñˇ�^˙?¨Û√∏D6O•Ìf¸Ò¶cReø+ÕΩı˚/∂%ªÆ◊2&~ù&ıß˝öd3Lã˝Äj�.≈DìÉ_^sçc�}q„=`1Ì�ﬂ	WMÁ‰rtµ∑0ÏÇò
(∑€Ht~{!BÖﬂªŒ#Ä™≥qcÕbR(˘}‹ˇn
›˛∆rlu?ág¯pÈêã⁄DazpúØ$6vú=I�„ v>Krc˛’®23üH	Ki¶öi¶¨qk¥_Nù»&¥ÓÓ!Ó·^¥¢â£ÿ2ùq1†±—�02Œ7≥+.ÉûYÒ›R∞u¨ïfeÁµ9MxÚ=7Öëj´Àa‡-]≤gkÏS.üGªÏ÷ƒ ø>Ÿ5]¸¢U}x•Gf
h¶b L≈�2Ù+84æ°¯å*ö∑ıLy‹FØîmEYjÍ0(£«?
∏¿
?C*dãı{ı≥…$:~}Íº+øæqNÜ⁄`ÒÖ;≥sûúß∞}˜ﬂ}˜ﬂ}˜ﬂ}˜ﬂ}£”G}ﬁ›¡U\ö~?≠Joˇ�à/b∆lœ"†�˘	�Ï÷Ç=?)ˆ+Ì,Ã$:IF∏éW;#CÄ�)UIXõo6E¢¯˝cUSy(ˆ/™4æ¶:Z¿H)G©£ûyÁûyÁûyÁûy„n–�¿c˚t!É6∏���∫ÎL‡[Zÿ#/∆}Tp€‰«ˇ�0Ì1BíŸ?·s÷Ù>úâR•Jî5ﬁ≤ï¿QEQEQEQEQEQEQEQEQEQE
u@=˘gkX
ˇ�‰£àÎµg∑®ù=! åuƒ<u4kT¥7(F4/¸·çÙl‘÷yÔ3—m∂€m∂€m∂€m∂€m∂€m∂€m∂€m∂€m∂€m∂€m∂◊˙†�Nå�VÖÁ™Ì˙küö≥àêHCπ˝l¨ÆÀ⁄]pìŒ‘ª””M4”M4”M4”M4”M4”M4”M4”M4”M4”M4”M1^†�Ø‡�OA§EÆ7Ù \ß∫.+àªd5aÛ¶˜€KÆ≥5i¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶öi¶òØP�H»�ç–ˇ�������������*x397787K*x286693W*rC&l0HE%-12345X
```

Well, the headings at the top are useful, but the rest seems to be junk. Let's look at the heading:
```
%-12345X@PJL JOB NAME="wrap in 'n00bz{}'"
%-12345X@PJL JOB USERNAME="0xBlue"
%-12345X@PJL JOB TIMESTAMP="05/31/2022"
%-12345X@PJL JOB OSINFO="Blue0S"
%-12345X@PJL ENTER LANGUAGE=LAVAFLOW
```

Looks like we found the language, which is *lavaflow*. Let's try to see if we can convert this junk into some readable text. Searching up "lava flow print job decoder" brings up the following [link](http://manpages.ubuntu.com/manpages/trusty/man1/lavadecode.1.html). There seems to be a handy tool already built into Ubuntu. 

cd into the directory with *corrupt.lava* and perform the following command:

```
lavadecode <corrupt.lava
```

And, voila!

```
\033%-12345X@PJL JOB NAME="wrap in 'n00bz{}'"
\033%-12345X@PJL JOB USERNAME="0xBlue"
\033%-12345X@PJL JOB TIMESTAMP="05/31/2022"
\033%-12345X@PJL JOB OSINFO="Blue0S"
\033%-12345X@PJL ENTER LANGUAGE=LAVAFLOW
\033E            RESET
\033&l0S        DUPLEX: [off]
\033&l0G
\033&u146D        X RESOLUTION: [146]
\033&l154X        COPIES: [154]
\033&x157X        TRANSMIT ONCE COPIES: [157]
\033&l0O        ORIENTATION: [port]
\033r157U        NBIE: [5]
\033g162W        BW/COLOR: [162]
            fmt=2 np=1
            BLACK:    X=1200, Y=600, unk=0, #=4(2)
ch=0x38 ()
ch=0xe3 ()
ch=0x8e ()
ch=0x38 ()
ch=0xe3 ()
ch=0x8e ()
ch=0x38 ()
ch=0xe3 ()
ch=0x8e ()
ch=0x38 ()
ch=0xe3 ()
ch=0x8e ()
ch=0x38 ()
ch=0xd0 ()
ch=0xcd ()
ch=0xbf ()
ch=0x90 ()
ch=0x0 ()
ch=0x0 ()
ch=0x0 ()
ch=0x0 ()
ch=0x3 ()
ch=0xe6 ()
ch=0x38 ()
ch=0x1a ()
ch=0x4 ()
ch=0x80 ()
ch=0x0 ()
ch=0x0 ()
ch=0x0 ()
ch=0x1 ()
ch=0x5e ()
ch=0x7e ()
ch=0x0 ()
ch=0x5a ()
ch=0x91 ()
ch=0x81 ()
ch=0x50 ()
ch=0xc7 ()
ch=0xa6 ()
ch=0xca ()
ch=0xe7 ()
ch=0xa8 ()
ch=0xd0 ()
ch=0x14 ()
ch=0x2c ()
ch=0xbc ()
ch=0xe5 ()
ch=0x46 ()
ch=0x25 ()
ch=0x8d ()
ch=0x8b ()
ch=0x88 ()
ch=0x71 ()
ch=0x49 ()
ch=0x6f ()
ch=0xf4 ()
ch=0xb2 ()
ch=0x18 ()
ch=0x32 ()
ch=0x9 ()
ch=0xd4 ()
ch=0x1d ()
ch=0x3b ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xfb ()
ch=0xef ()
ch=0xbe ()
ch=0xf5 ()
ch=0x16 ()
ch=0x40 ()
ch=0x0 ()
ch=0x0 ()
ch=0x25 ()
ch=0x40 ()
ch=0x40 ()
ch=0x0 ()
ch=0x0 ()
ch=0x9a ()
ch=0xc1 ()
ch=0xb ()
ch=0xee ()
ch=0x24 ()
ch=0x9a ()
ch=0x6f ()
ch=0xd2 ()
ch=0xa4 ()
ch=0x96 ()
ch=0xe1 ()
ch=0x2f ()
ch=0x47 ()
ch=0x78 ()
ch=0x2 ()
ch=0xbe ()
ch=0xd4 ()
ch=0x1c ()
ch=0x15 ()
ch=0x38 ()
ch=0x61 ()
ch=0x8b ()
ch=0x8 ()
ch=0x7c ()
ch=0xe3 ()
ch=0xde ()
ch=0x1d ()
ch=0x92 ()
ch=0x16 ()
ch=0xbe ()
ch=0x17 ()
ch=0x4a ()
ch=0xa4 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x92 ()
ch=0x49 ()
ch=0x24 ()
ch=0x91 ()
ch=0x6c ()
ch=0x70 ()
ch=0x0 ()
ch=0x0 ()
ch=0x2e ()
ch=0x21 ()
ch=0x0 ()
ch=0x0 ()
ch=0x7 ()
ch=0x5c ()
ch=0x98 ()
ch=0x7f ()
ch=0x2e ()
ch=0x2b ()
ch=0x72 ()
ch=0x7e ()
ch=0x99 ()
ch=0x7 ()
ch=0xe4 ()
ch=0xac ()
ch=0xc5 ()
ch=0x22 ()
ch=0x22 ()
ch=0x11 ()
ch=0xf0 ()
ch=0xec ()
ch=0x7e ()
ch=0xdb ()
ch=0xb ()
Error: c=240 
```

At the bottom, we have the potential suspect, "c=240". I searched for any possible hints to what "c=240" is. Could it mean 240 Celsius? Well, no. This is the part where I asked 0xBlue for a kind hint. He provided me with these hints:

- The 3-digit numbers at the top are the key to finding the flag
- You may realize that these range from roughly between 140 to 170.
- What is something that is around 30?

Sounds like the alphabet! He also mentioned the 3-digit numbers, let's take a look at that:

```
\033%-12345X@PJL JOB NAME="wrap in 'n00bz{}'"
\033%-12345X@PJL JOB USERNAME="0xBlue"
\033%-12345X@PJL JOB TIMESTAMP="05/31/2022"
\033%-12345X@PJL JOB OSINFO="Blue0S"
\033%-12345X@PJL ENTER LANGUAGE=LAVAFLOW
\033E            RESET
\033&l0S        DUPLEX: [off]
\033&l0G
\033&u146D        X RESOLUTION: [146]
\033&l154X        COPIES: [154]
\033&x157X        TRANSMIT ONCE COPIES: [157]
\033&l0O        ORIENTATION: [port]
\033r157U        NBIE: [5]
\033g162W        BW/COLOR: [162]
            fmt=2 np=1
            BLACK:    X=1200, Y=600, unk=0, #=4(2)
```
