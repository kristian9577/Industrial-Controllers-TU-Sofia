# Industrial-Controllers-TU-Sofia

# Постояннотокови електрически машини (ПТМ)
Електрическите машини за постоянен ток са обратими, т.е при захранване с постоянно напрежение работят като двигатели, а при задвижване от вън работят като генератори. Използват се главно като двигатели и сравнително по-рядко като генератори. Двигателите имат възможност за плавно и икономично регулиране на честотата на въртене в широки граници и за получаване на желани механични характеристики и голям пусков момент. Използват се като тягови двигатели в електротранспорта, за задвижване на металорежещи машини, подемно-транспортни машини, като изпълнителни звена в системи за автоматично регулиране. Генераторите се използват за захранване на двигатели за постоянен ток, електрозаваръчни агрегати, електромагнити и апаратура за управление и контрол, а някои специални генератори – като усилватели на управляващи сигнали и като тахогенератори за измерване на честота на въртене. Основен недостатък на машините за постоянен ток е наличието на колекторно-четков апарат. Неговото предназначение е да превключва по подходящ начин котвената намотка така, че във външната верига (в консуматора) да се получава постоянно по посока е.д.н. в генераторен режим или на вала на машината да се създава постоянен по посока електромагнитен момент при двигателен режим.

# Принципът на действие на генераторите за постоянен ток 
Основава на явлението електромагнитна иднукция. Нека между полюсите N и S на постоянен магнит или електромагнит се върти с постоянна скорост цилиндър от феромагнитен материал с навивка, разположена диаметрално върху него (фиг. 5.10). Краищата на навивката са свързани с два изолирани един от друг медни сегмента, които се въртят заедно с нея. Върху сегментите опират неподвижни четки, които са свързани с потребителя (резистора R). При въртенето се изменя магнитният поток Ф, обхванат от намотката, и съгласно закона на електромагнитната индукция във всеки активен проводник (частта от навивката, която пресича магнитните линии на полето) се индуктира е.д.н. еx=BXlV
, където l и V са съответно дължината и линейната скорост на проводника, Bx - магнитната индукция в мястото, където се намира проводникът. Тъй като l и V са постоянни величини, е.д.н. е е пропорционално на магнитната индукция и следователно то се изменя във времето по същия начин както магнитната индукция под полюсите. Поради наличието на специално оформени полюсни накрайници разпределението на магнитната индукция под полюсите е близко до трапецовидно (фиг. 5.11).![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-10.PNG)

Следователно по същия начин се изменя и е.д.н. при изменение на положението на навивката (ъгъл α) в междуполюсното пространство. При това е.д.н. се изменя не само по големина, но и по посока, т.е. индуктираното е.д.н. е променливо, защото активните проводници на навивката пресичат последователно магнитното поле под разноименните полюси (фиг. 5.11 а). От фиг. 5.10 се вижда, че четка 1 през съответния сегмент има връзка само с проводник, който се намира под полюса N, а четка 2 – с проводник под полюса S. При смяна на полюса, под който се намира проводникът, се сменя и четката, към която контактува съответният сегмент, поради което е.д.н. е между четките и токът i през потребителя R запазват посоката си постоянна (фиг. 5.11 б) независимо от това, че индуктираното е.д.н. е променливо. Устройството, съставено в случая от два сегмента, с които контактуват четките, се нарича колектор и служи като токоизправител – променливият ток в навивката протича през товарния резистор като пулсиращ ток. Пулсациите на е.д.н. и тока се намаляват при увеличаване на броя на навивките, които се разпределят равномерно по повърхността на цилиндъра, като съответно се увеличава и броя на сегментите (колекторните пластини).![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-11.PNG)


За най-пълно и ефективно (без искрене) изправяне на променливия ток е необходимо смяната на четката да става в момент, когато индуктираното е.д.н. в навивката е нула, т.е. активните й проводници да се намират на геометричната неутрална линия (г.н.л.) (фиг. 5. 12), която лежи в равнината, разделяща пространството между два съседни разноименни полюса. ![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-12.PNG)


# Принципът на действие на двигателя за постоянен ток 
Основава се на взаимодействието на магнитното поле на индуктора с електрическия ток, протичащ през котвата, при възниква електромагнитна сила и се създава електромагнитен момент. Ако резисторът от фиг. 5.10 се изключи и към четките се включи източник със същия поляритет (фиг. 5. 12), през навивката ще протече ток с посочената на фигурата посока. От взаимодействието на този ток и магнитното поле възникват електромагнитни сили F. Те създават двигателен момент, който завърта навивката. За да се запази посоката на момента постоянна, когато активните проводници преминават от един полюс към друг, е необходимо в съответния момент да се промени посоката на тока в навивката. Следователно предназначението на колектора при двигателен режим е да преобразува постоянния ток (във вътрешната верига) в променлив (в навивката), за да се получи постоянен по посока момент.

При двигателен режим под действие на електромагнитния момент навивката се върти, активните й проводници пресичат магнитните линии на полето и в тях се индуктира е.д.н. Неговата посока е обратна на посоката на тока, поради което се нарича противо - е.д.н. 
При генераторен режим, когато към четките се свърже потребител, през навивката протича ток. Той си взаимодейства с магнитното поле и възниква електромагнитна сила, която създава момент. Неговата посока е обратна на посоката на механичния момент, който върти вала.

На фиг. 5.13а е показан общият вид на електрическа машина за постоянен ток:![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-13.PNG)

1 – вал; 2 – лагерен щит; 3 – колектор; 4 – четкова система; 5 – котвен пакет; 6 –полюсно тяло; 7 – възбудителна бобина; 8 – тяло; 9 – лагерен щит; 10 – вентилатор; 11 – укрепване на челните съединения на котвената намотка; 12 – тяло.
На фиг. 5.13б е показана разглобена електрическа машина за постоянен ток и означени най-важните й съставни части:
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-13b.PNG)




# Е.д.н. и електромагнитен момент на машините за постоянен ток
 Е.д.н. на машината е равно на алгебричната сума от моментните стойности на е.д.н. ex в активните проводници на секциите, включени в един паралелен клон E=pN/2πα ΩФ=cΩФ, където c=pN/2πα; N – броя на активните проводници на секциите, включени в един паралелен клон; p – броят на двойките полюси; 2a – броят на паралелните клонове; Ω – ъгловата скорост на машината; Ф – магнитният поток на един полюс, Wb.
Ако вместо с ъглова скорост Ω се работи с честота на въртене n=60Ω/2πα, min-1 , за е.д.н. се получава  E=pN/60α nФ=C_e nФ , където C_e=pN/60α


При генераторен режим посоката на е.д.н. Е съвпада с посоката на тока и то определя напрежението U на изводите на генератора (фиг. 5.14 а). При двигателен режим посоката му е обратна на посоката на тока и то уравновесява напрежението U, захранващо двигателя (фиг. 5.14 б). Уравненията на електрическото състояние или уравненията на напреженията на машината при установен режим (Ia=const. и Ω=const.). 
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-14.PNG)

За електрическите схеми от фиг. 5.14 се получават съгласно втория закон на Кирхоф и имат вида:
U=E-R_a I_a  – при генераторен режим;
U=E+R_a I_a – при двигателен режим.

Токът във всеки активен проводник на котвената намотка е равен на тока в един паралелен клон i_a=I_a/2α , където Ia е общият ток на машината.


При взаимодействието на магнитния поток и тока в проводника възниква електромагнитна сила Fx, която създава електромагнитния момент на вала на машината. Електромагнитният момент на машината се получава като се сумират моментите, действащи върху всички проводници, или като се умножи сумата от моментите, действащи върху проводниците под един полюс, чийто брой е N/2p, по броя на полюсите 2p: M=pN/2πα ФI_a=cФI_a , където c=pN/2πα; N – броя на активните проводници на секциите, включени в един паралелен клон; p – броят на двойките полюси; 2a – броят на паралелните клонове; Ω – ъгловата скорост на машината; Ia – общият ток на машината; Ф – магнитният поток на един полюс, Wb.


Както се вижда, моментът е пропорционален на произведението на магнитния поток на всеки полюс и котвения ток на машината. Той е съпротивителен при генераторен режим на машината и въртящ при двигателен режим на машината. 
При празен ход на машината на валай действа и т.нар. момент на празен ход М0. Той съответства на мощността Р0 , която машината трябва да получи при празен ход, за да се покрият загубите от триене и загубите в магнитопровода от хистерезис и вихрови токове: M_0=P_0/Ω Този момент е съпротивителен и много по-малък от М.

При генераторен режим въртящ е моментът на задвижващия двигател М1, а съпротивителни са електромагнитният момент М и моментът на празен ход на генератора М0.
 При двигателен режим въртящ е моментът М, а съпротивителни са моментът на задвижвания механизъм М2 и моментът на празен ход М0.
 При установен режим (Ia=const. и Ω=const.) на работа на машината съществува равновесие между въртящия и сумата от съпротивителните моменти. Уравненията за механичното състояние или уравненията на моментите на машината при установен режим са :
M_1=M_C=M+M_0≈M  – при генераторен режим;
M=M_C=M_2+M_0≈M_2   – при двигателен режим.
Двигателните моменти са положителни, ако действат по посока на движението, а съпротивителните – ако са насочени обратно на движението.

# Начини за възбуждане на машините за постоянен ток.
В зависимост от начина на захранване на възбудителната намотка машините за постоянен ток биват:
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-15.PNG)
1. Машини с паралелно възбуждане (шунтови) – възбудителната намотка се включва паралелно на котвената намотка (фиг. 5. 15 а) и I=Ia – Iв за генераторен, а I=Ia + Iв за двигателен режим; 
2. Машини с независимо възбуждане – възбудителната намотка не е свързана с котвата, а се захранва от отделен (независим) източник (фиг. 5. 15 б) (в малките машини магнитният поток може да се създава от постоянни магнити); 
3. Машини с последователно възбуждане (серийни) – възбудителната намотка се включва последователно на котвената намотка (фиг. 5. 15 в) и I=Ia = Iв ; 
4. Машини със смесено възбуждане (компаундни) – имат две възбудителни намотки, едната от които се включва паралелно (ВН1), другата – последователно (ВН2) на котвената намотка (фиг. 5. 15 г) и I=IB2 =Ia – IB1 за генераторен, а I=IB2 =Ia + IB1 за двигателен режим. Възбудителната намотка за последните три вида машини е свързана с котвата. Те се наричат машини със смесено възбуждане. 

# Механични характеристики на двигателите за постоянен ток

Под механична характеристика се разбира зависимостта между ъгловата скорост и момента M=f(Ω). Изменението на ъгловата скорост зависи от наклона на механичната характеристика спрямо абсцисната ос. Колкото по-малък е този наклон, т.е. колкото „по-твърда“ е механичната характеристика, толкова изменението на скоростта ще се влияе по-малко от изменението на натоварването на двигателя. 
За постояннотоковите двигатели е характерно свойството саморегулиране. Саморегулирането се изразява в това, че при изменение на статичния съпротивителен момент на вала се изменят автоматично котвеният ток и ъгловата скорост, при които двигателят работи устойчиво. Ролята на регулатор играе противо-е.д.н. Е=cФΩ, индуктирано в котвената намотка. 
Електродвигателите задвижват съответни производствени механизми и заедно с тях образуват агрегати. Под устойчива работа на агрегата се разбира способността на двигателя да заеме отново състояние на равновесие (М=Mc) при извеждането му от него. Условието за устойчива работа изисква определено съответствие между механичните характеристики на двигателя M=f(Ω) и задвижвания механизъм Mс=f(Ω).




При механичните характеристики, показани на фиг. 5. 16 а, агрегатът ще работи устойчива, защото при всяка промяна на ъгловата скорост по отношение на установената Ωу , отговаряща на т. А, се появява неуравновесен момент, под действие на който агрегатът се връща към установената скорост Ωу . При механичните характеристики, показани на фиг. 5. 16 б, работата на агрегата ще бъде неустойчива, защото неуравновесеният момент при Ω≠Ωу действа в посока на отдалечаване на ъгловата скорост от установената скорост Ωу . 
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-16.PNG)

 # Механични характеристики на постояннотоков двигател с независимо възбуждане
 Двигателят с независимо възбуждане намира най-широко приложение. Когато двигателят работи при естествени условия, а именно U=UH, IB=IBH (Ф=ФН), и в котвената му верига не са включени допълнителни резистори, съответната му механична характеристика се нарича естествена. Ако не е изпълнено някое от тези условия, механичната характеристика е изкуствена. Различаваме следните видове изкуствени механични характеристики (фиг. 5.17 а, б, в):
 ![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-17.PNG)


# Механични характеристики на постояннотоков двигател с последователновъзбуждане
 При двигателя с последователно възбуждане последователно на котвената и възбудителната намотка е включен пусков резистор, който може да бъде оразмерен и за продължителна работа и да служи като регулиращ. 
Двигателите за постоянен ток с последователно възбуждане са подходящи за работа при тежки условия и при претоварване.

![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-18.PNG)
Механичната характеристика M=f(Ω) е показана на фиг. 5.18. Естествената механична характеристика на двигателя с последователно възбуждане при U=UH=const. и RП=0 е близка до хипербола. Ако съпротивлението на резистора RП е различно от нула, се получават семейство изкуствени характеристики, които са разположени под естествената. 
Съществена особеност на двигателя с последователно възбуждане е, че той не трябва да работи ненатоварен. При празен ход М=0, Iа=0 и Ф≡ Iа≈0, при което ъгловата скорост достига опасни стойности (Ω → ∞).



# Пускане и регулиране на скоростта на двигатели за постоянен ток
 Пускане
 Токът в котвената намотка е  I_a=(U-E)/R_a  . В първия момент след включването роторът на двигателя не се върти, поради което липсва противо- е.д.н. (Е=cФΩ=0) и началният пусков ток е I_п=U/R_a . Тъй като съпротивлението на котвената намотка е малко, пусковият ток превишава номинални 10 – 30 пъти. Този голям пусков ток е опасен за колектора и четките. Освен това води и до голям пусков момент МП. Пусковият ток може да се намали по два начина: 
•Чрез включване в котвената намотка на пусков резистор (реостатно пускане); 
•Чрез намаляване на захранващото напрежение (когато това е технически възможно. 
Реостатно пускане. След включване на двигателя той се ускорява, противо- е.д.н.се увеличава и пусковият ток намалява. Това позволява постепенно да се намалява съпротивлението на пусковия резистор в процеса на пускане на двигателя. Обикновено пусковият резистор има няколко степени. Те се оразмеряват така, че при изключването им пусковият ток, съответно моментът на двигателя, да се изменя в определени граници (IП1 и IП2, съответно МП1 и МП2).
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-19.PNG)
На фиг. 5.19 са показани механичните характеристики и е изяснен пусковия процес при постояннотоков двигател с паралелно възбуждане (фиг. 5.19а) и постояннотоков двигател с последователно възбуждане (фиг. 5.19б). В ляво е показан пусков резистор с четири степени. Пусковият процес започва от механична характеристика 1 при МП1< МС. След като ъгловата скорост нарасне до Ω1, при която М=МП2, се изключва първата степенна пусковия резистор и т.н. След изключване на последната степен на пусковия резистор процесът протича по естествената механична характеристика 4 до Ω4, съответстваща на установен режим (М=МС).
 

# Регулиране на скоростта
 От зависимостта Ω=U/cФ-R_a/〖(cФ)〗^2  M  става ясно, че ъгловата скорост на двигателя за постоянен ток може да регулира чрез: 
	Изменение на съпротивлението в котвената верига (Ra+Rp); 
	Изменение на магнитния поток Ф, т.е. на възбудителния ток; 
	Изменение на захранващото напрежение U, при което се получават съответните изкуствени механични характеристики. 
1.Двигатели с независимо и паралелно възбуждане. 
•Регулиране на ъгловата скорост чрез изменение на съпротивлението на котвената верига – от фиг. 5.17а се вижда, че при увеличаване на съпротивлението на регулиращия реостат двигателният и съпротивителният момент (М=МС) се изравняват при по-ниска ъглова скорост, т.е. ъгловата скорост намалява.
 Предимства: 
o Широк обхват на регулиране; 
o Лесно осъществяване. Недостатъци: 
o Големи загуби на електрическа енергия в регулиращия реостат; 
o Намаляване на твърдостта на механичната характеристика при понижени скорости. 


Регулиране чрез изменение на магнитния поток – осъществява се чрез резистор, включен във възбудителната верига. От фиг. 5.17б се вижда, че чрез изменение на магнитния поток ъгловата скорост може да се изменя в широки граници. Зависимостта на ъгловата скорост от възбудителния ток Ω=f(IB) при U=const. и МС =const. се нарича регулираща характеристика (фиг.5.20). 
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/fig5-20.PNG)
Постояннотокови електрически машини (ПТМ) При ненаситена машина Ф≡IB регулиращата характеристика е хипербола.Предимства: 
	Плавно; 
	Икономично; 
	При нарастване на ъгловата скорост нараства к.п.д. и полезната мощност. 
•Регулиране чрез изменение на напрежението. Предимства: 
	Широк обхват; 
	Плавност; 
	Икономичност и запазване на стабилността (твърдостта) на характеристиката. 
Недостатъци: 
	Висока стойност; понижен к.п.д. на устройството за изменение на напрежението 
2.Двигатели с последователно и смесено възбуждане 
•Регулиране на ъгловата скорост чрез изменение на съпротивлението на котвената верига - осъществява се чрез регулиращ резистор, включен в котвената верига (фиг.5.18). 
Предимства: 
	Простота и сигурност; Недостатъци: 
	Висока стойност; 
•Регулиране чрез изменение на магнитния поток – паралелно на възбудителната или на котвената намотка се включва шунтиращ резистор, чрез който може да се регулира възбудителния ток.
 3. Импулсен метод за регулиране на ъгловата скорост на двигателите за постоянен ток – осъществява се чрез управляеми включващо – изключващи прекъсвачи, които се включват в котвената верига на постояннотоковия двигател. Регулирането се извършва практически без загуба на мощност, особено при високи ъглови скорости. 
Двигателите за постоянен ток се използват, когато е необходимо плавно регулиране на ъгловата скорост в широки граници, при необходимост от високи ъглови скорости, голям пусков момент и специални механични характеристики.


# Блокова схема
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/block-schema.PNG)

# Пълна принципна схема
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/principal.PNG)

# Симулационна схема
![alt text](https://github.com/kristian9577/Industrial-Controllers-TU-Sofia/blob/master/picture/simulation.PNG)
