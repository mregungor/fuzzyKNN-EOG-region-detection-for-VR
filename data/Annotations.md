# EXPERIMENT ANNOTATIONS
with MATLAB &| PYTHON Index Assignments
### <u>Experiment 0</u> <br>
T.append([0,0]);

### <u>Experiment 1 : Page Center to Right Page Center </u><br>
#T{1}=1:443;     % 0-5 sec. <br>
T.append([0,442]);

### <u>Experiment 2 : Page Center to Right Page Center to Page Center </u><br>
#T{2}=444:843;   #5-9 sec. <br>
T.append([443,842]);

### <u>Experiment 3 : Page Center to Left Page Center</u> <br>
#T{3}=844:1143;  % 9-12 sec. <br>
T.append([843,1142]);

### <u>Experiment 4 : Page Center to Left Page Center to Page Center </u><br>
#T{4}=1144:1543; % 12-16 sec.<br>
T.append([1143,1542]); <br>

### <u>Experiment 5 -8 : Same Experiments 1-4 </u><br>
##% T{5}=1544:1943; % 16-20 sec. <br>
#T{5}=1600:1943; % 16-20 sec. %Cut <br>
T.append([1599,1942]); <br>
#T{6}=1944:2443; % 20-25 sec. <br>
T.append([1943,2442]); <br>
#T{7}=2444:2743; % 25-28 sec. <br>
T.append([2443,2742]); <br>
#T{8}=2744:3243; % 28-33 sec.<br>
T.append([2743,3242]); <br>

### <u>Experiment 9 : Page Center to Page Upper Center </u><br>
#T{9}=3244:3643; %33-37 sec. <br>
T.append([3243,3642]); <br>

### <u>Experiment 10: Page Center to Page Upper Center to Page Center </u><br>
#T{10}=3644:4243;%37-43 sec <br>
T.append([3643,4242]); <br>

### <u>Experiment 11: Page Center to Page Down Center </u><br>
#T{11}=4244:4643;%43-47sec <br>
T.append([4243,4642]); <br>

### <u>Experiment 12: Page Center to Page Down Center to Page Center </u><br>
#T{12}=4644:5243;%47-53 sec <br>
T.append([4643,5242]); <br>

### <u>Experiment 13: Still Focus on Page Center 6sec </u><br>
#T{13}=5244:5843;%53-59 sec. <br>
T.append([5243,5842]); <br>

### <u>Experiment 14: Still Focus on Page Center 15sec </u><br>
#T{14}=5844:7343;%59-74 sec <br>
T.append([5843,7342]); <br>

### <u>Experiments 15-18: Same Experiments as 9-12 </u> <br>
#T{15}=7344:7843;%74-79sec   -- 79-87 errors <br>
T.append([7342,7842]); <br>

#T{16}=8643:9243;%87-93sec <br>
T.append([8642,9242]);<br>

#T{17}=9244:9943;%93-100 sec <br>
T.append([9243,9942]);<br>

#T{18}=9944:10643;%100-107 sec <br>
T.append([9943,10642]);<br>

### <u>Experiments 19-22: Same Experiments as 1-4 </u><br>
#T{19}=10644:11343;%107-114 <br>
T.append([10643,11342]); <br>
#T{20}=11344:12143;%114-122 <br>
T.append([11343,12142]); <br>
#T{21}=12144:12643;%122-127 <br>
T.append([12143,12642]); <br>
#T{22}=12644:13243;%127-133 <br>
T.append([12643,13242]); <br>

### <u>Experiments 23-26: Same Experiments as 9-12 </u><br>
#T{23}=13244:13643;%133-137 <br>
T.append([13243,13642]); <br>
#T{24}=13644:14243;%137-143 <br>
T.append([13643,14242]); <br>
#T{25}=14244:14743;%143-148 <br>
T.append([14243,14742]); <br>
#T{26}=14744:15543;%148-156 <br>
T.append([14743,15542]); <br>

### <u>Experiment 27 : Center to Right Upper Corner </u><br>
#T{27}=15544:15943;%156-160 <br>
T.append([15543,15942]); <br>
#%Experiment 28 : Center to Right Upper Corner to Center <br>
#T{28}=15944:16443;%160-165 <br>
T.append([15943,16442]); <br>
#%Experiment 29 : Center to Lower Right Corner <br>
#T{29}=16444:16943;%165-170 <br>
T.append([16443,16942]); <br>
#%Experiment 30 : Center to Lower Right Corner to Center <br>
#T{30}=16944:17643;%170-177 <br>
T.append([16943,17642]); <br>
#%Experiment 31 : Center to Lower Left Corner <br>
#T{31}=17644:18243;%177-183 <br>
T.append([17643,18242]);<br>
#%Experiment 32 : Center to Lower Left Corner to Center <br>
#T{32}=18244:19143;%183-192 <br>
T.append([18243,19142]); <br>
#%Experiment 33 : Center to Upper Left Corner <br>
#T{33}=19144:19743;%192-198 <br>
T.append([19143,19742]); <br>
#%Experiment 34 : Center to Upper Left Corner to Center <br>
#T{34}=19744:20643;%198-207 <br>
T.append([19743,20642]); <br>
<hr>

## These Experiments are Out of the Page from center of the page <br>
### <u>Experiment 35 : From Center of the page to 12cm right out of the page </u> <br>
#T{35}=20644:21143;%207-212 <br>
T.append([20643,21142]); <br>
### <u>Experiment 36 : From the Page Center to 30cm Right out of the page </u><br>
#T{36}=21144:21743;%212-218 <br>
T.append([21143,21742]); <br>
### <u>Experiment 37 : From the Page Center to 12cm Left Out of the page </u><br>
#T{37}=21744:22443;%218-225 <br>
T.append([21743,22442]); <br>
### <u>Experiment 38 : From the Page Center to 30 cm Left out of the page </u><br>
#T{38}=22444:23143;%225-232 <br>
T.append([22443,23142]); <br>
### <u>Experiment 39 : From the Page Center to 12 cm of the Up from page </u><br>
#T{39}=23144:23743;%232-238<br>
T.append([23143,23742]);<br>
### <u>Experiment 40 : From the Page Center to 30 cm Up from the page </u><br>
#T{40}=23744:24343;%238-244<br>
T.append([23743,24342]);<br>
### <u>Experiment 41 : From the Page Center to 12 cm Down from the page </u><br>
#T{41}=24344:24743;%244-248<br>
T.append([24343,24742]);<br>
### <u>Experiment 42 : From the Page Center to 30 cm Down from the page </u><br>
#T{42}=24744:25443;%248-255<br>
T.append([24743,25442]);<br>
<hr><br>

## FULL SCALE PAGE READING EXPERIMENT <br>
### <u>Experiment 43 : Full Scale Page Reading from Upper Left to End Right Down </u><br>
#T{43}=25444:42943;%255-430 <br>
T.append([25443,42942]); <br>
<hr>


## OUT OF PAGE FOCUS FROM PAGE SAMPLES HORIZONTAL(28 - 1:12) <br>
<hr>
### <u>Experiment 44-47: Page Bottom Right to Right out of the page side focus </u><br>
#T{44}=42944:43543;%430-436 <br>
T.append([42943,43542]); <br>
#T{45}=43544:44443;%436-445 <br>
T.append([43543,44442]); <br>
#T{46}=44444:45443;%445-455 <br>
T.append([44443,45442]); <br>
#T{47}=45444:45743;%455-458 <br>
T.append([45443,45742]); <br>

### <u>Experiment 48: Page Center to Out of Page Right </u><br>
#T{48}=45744:46143;%458-462 <br>
T.append([45743,46142]); <br>
### <u>Experiment 49: Page Upper Center to Out of Page Right </u><br>
#T{49}=46144:46743;%462-468 <br>
T.append([46143,46742]); <br>

### <u>Experiment 50-53:  Page Bottom Right to Out of the page Left Side Focus </u><br>
#T{50}=46744:47143;%468-472<br>
T.append([46743,47142]); <br>
#T{51}=47144:47443;%472-475 <br>
T.append([47143,47442]); <br>
#T{52}=47444:48243;%475-483 <br>
T.append([47443,48242]); <br>
#T{53}=48244:49143;%483-492 <br>
T.append([48243,49142]); <br>

### <u>Experiment 54: Page Center to Out of Page Left Side focus </u><br>
#T{54}=49144:49743;%492-498 <br>
T.append([49143,49742]); <br>
### <u>Experiment 55: Page Upper Center to Out of Page Left Side focus </u><br>
#T{55}=49744:50343;%498-504 <br>
T.append([49743,50342]); <br>
<hr>

## OUT OF PAGE FOCUS FROM PAGE SAMPLES VERTICAL(29 - 1:13) <br>

<hr>

### <u>Experiments 56-57: Page Upper Center (Title) to out of page Upper </u><br>
#T{56}=50344:50843;%504-509 <br>
T.append([50343,50842]); <br>
#T{57}=50844:51743;%509-518 <br>
T.append([50843,51742]); <br>

## <u>Experiments 58-59: Page Center to out of page Upper focus </u><br>
#T{58}=51744:52343;%518-524 <br>
T.append([51743,52342]); <br>
#T{59}=52344:52843;%524-529 <br>
T.append([52343,52842]); <br>
#%ERROR 529-534 signals

## <u>Experiments 60-61: Page Bottom Left to out of Page Upper focus </u><br>
#T{60}=53344:54043;%534-541 <br>
T.append([53343,54042]); <br>
#T{61}=54044:54843;%541-549 <br>
T.append([54043,54842]); <br>

### <u>Experiments 62-63: Page Bottom Left to out of Page Down focus </u><br>
#T{62}=54844:55543;%549-556 <br>
T.append([54843,55542]); <br>
#T{63}=55544:56143;%556-562 <br>
T.append([55543,56142]); <br>

## <u>Experiments 64-65: Page Center to out of Page Down focus </u><br>
#T{64}=56144:56743;%562-568 <br>
T.append([56143,56742]); <br>
#T{65}=56744:57243;%568-573 <br>
T.append([56743,57242]); <br>
 
## <u>Experiments 66-67: Page Upper Center(Title) to out of Page  Down focus </u><br>
#T{66}=57343:57743;%574-578 <br>
T.append([57342,57742]); <br>
#T{67}=57744:58543;%578-586 <br>
T.append([57743,58542]); <br>
<br>
<hr>
<br>

## *STILL FOCUS - RANDOM TESTS IN-PAGE (30-1:5) AND OUT-OF-PAGE (31-1:5) <br>
<hr>
<br>

### <u>Experiment 68-72 (5): Still In-Page Focus Tests </u><br>
#T{68}=58544:59143;%586-592   %Page In Regions <br>
T.append([58543,59142]); <br>
#T{69}=59144:59743;%592-598   %Page in Down Center <br>
T.append([59143,59742]); <br>
#T{70}=59744:60243;%598-603   %Page In Right Center <br>
T.append([59743,60242]); <br>
#T{71}=60244:61143;%603-612   %Page In Upper Center1 <br>
T.append([60243,61142]); <br>
#T{72}=61144:61543;%612-616   %Page In Left Center <br>
T.append([61143,61542]); <br>
<br>

### <u>Experiment 73-77 (5): Still Out-of-Page Focus Tests </u><br>
#T{73}=61544:62143;%616-622 <br>
T.append([61543,62142]); <br>
#T{74}=62144:62743;%622-628 <br>
T.append([62143,62742]); <br>
#T{75}=62744:63243;%628-633 <br>
T.append([62743,63242]); <br>
#T{76}=63244:63743;%633-638 <br>
T.append([63243,63742]); <br>
#T{77}=63744:64343;%638-644 <br>
T.append([63743,64342]); <br>
<br>
<hr>
<br>

## *CHANGE FOCUS - RANDOM TESTS IN-PAGE TO OUT-OF-PAGE (32-1:5) <br>
<hr>

### <u>Experiment 78-82 (5) : From Page In to Out of the page focus </u><br>
#T{78}=64344:64943;%644-650   %Right side out of the page <br>
T.append([64343,64942]); <br>
#T{79}=64944:65543;%650-656	%(Same Experiment With T78) <br>
T.append([64943,65542]); <br>
#T{80}=65544:65943;%656-660   %Up side out of the page <br>
T.append([65543,65942]); <br>
#T{81}=65944:66343;%660-664   %Left side out of the page <br>
T.append([65943,66342]); <br>
#T{82}=66344:67143;%664-672   %Bottom side out of the page <br>
T.append([66343,67142]); <br>
<hr>
<br>

## *CHANGE FOCUS - RANDOM TESTS PAGE CENTER TO INPAGE LOCATIONS (33-1:4) <br>
#T{83}=67144:67543;%672-676   %Center to Right Upper <br>
T.append([67143,67542]); <br>
#T{84}=67544:67743;%676-678   %Center to Left Upper <br>
T.append([67543,67742]); <br>
#T{85}=67744:68143;%678-682   %Center to Left Bottom <br>
T.append([67743,68142]); <br>
#T{86}=68144:68943;%682-690   %Center to Right Bottom <br>
T.append([68143,68942]); <br>
<br>
<hr>
<br>

## *CHANGE FOCUS - RANDOM TESTS PAGE CENTER TO OUT-OF-PAGE LOCATIONS(34-1:8) <br>
#T{87}=68944:69343;%690-694   %Right Places Unknown <br>
T.append([68943,69342]); <br>
#T{88}=69344:69943;%694-700   %Right Places Unknown <br>
T.append([69343,69942]); <br>
#T{89}=69944:70743;%700-708   %Left Places Unknown <br>
T.append([69943,70742]); <br>
#T{90}=70744:71143;%708-712   %Left Places Unknown <br>
T.append([70743,71142]); <br>
<br>
#T{91}=71144:71743;%712-718   %Upper Places Unknown <br>
T.append([71143,71742]); <br>
#T{92}=71744:72543;%718-726   %Upper Places Unknown <br>
T.append([71743,72542]); <br>
#T{93}=72544:73243;%726-733   %Bottom Places Unknown <br>
T.append([72543,73242]); <br>
#T{94}=73244:74143;%733-742   %Bottom Places Unknown <br>
T.append([73243,74142]); <br>
<br>
<hr>
<br>

## *CHANGE FOCUS - RANDOM TESTS PAGE CENTER TO OUT-OF-PAGE CROSS LOCATIONS(35-1:4) <br>
#T{95}=74144:74743;%742-748   %Right Upper Cross <br>
T.append([74143,74742]); <br>
#T{96}=74744:75343;%748-754   %Left Upper Cross <br>
T.append([74743,75342]); <br>
#%754-759 ERROR Wave (75344:75843) <br>
#T{97}=75844:76343;%759-764   %Left Bottom Cross <br>
T.append([75843,76342]); <br>
#T{98}=76344:76943;%764-770   %Right Bottom Cross <br>
T.append([76343,76942]); <br>
<br>
<hr>
<br>

## *CHANGE FOCUS - RANDOM UNKNOWN LOCATIONS FROM PAGE CENTER (36-1:12)<br>

### <u>Experiment 99-102 : In Page Unknown Locations from center </u><br>
#T{99}=76944:77743;%770-778 <br>
T.append([76943,77742]); <br>
#T{100}=77744:78243;%778-783 <br>
T.append([77743,78242]); <br>
#T{101}=78244:79043;%783-791 <br>
T.append([78243,79042]); <br>
#T{102}=79044:79543;%791-796 <br>
T.append([79043,79542]); <br>

### <u>Experiment 103-110: Out-of-Page Unknown Locations from center </u><br>
#T{103}=79544:80143;%796-802 <br>
T.append([79543,80142]); <br>
#T{104}=80144:80643;%802-807 <br>
T.append([80143,80642]); <br>
#T{105}=80644:81143;%807-812 <br>
T.append([80643,81142]); <br>
#T{106}=81144:81743;%812-818 <br>
T.append([81143,81742]); <br>
#T{107}=81744:82143;%818-822 <br>
T.append([81743,82142]); <br>
#T{108}=82144:82543;%822-826 <br>
T.append([82143,82542]); <br>
#T{109}=82544:83143;%826-832 <br>
T.append([82543,83142]); <br>
#T{110}=83144:83843;%832-839 <br>
T.append([83143,83842]); <br>
<br>
<hr>

## *CHANGE FOCUS - PAGE CENTER TO (EXTREME CORNERs OF THE EYE) OUT LOCATIONS (36-13:18)<br>
#T{111}=83844:84543;%839-846  %Rightmost Edge from center <br>
T.append([83843,84542]); <br>
#T{112}=84544:85343;%846-854  %Uppermost Edge from center <br>
T.append([84543,85342]); <br>
#T{113}=85344:85943;%854-860  %Leftmost Edge from center <br>
T.append([85343,85942]); <br>
#T{114}=85944:86743;%860-868  %Lowermost Edge from center <br>
T.append([85943,86742]); <br>
##% T{115}=86744:87543;%868-876  %Lowermost Edge from center (may be because of blinking) <br>
#T{115}=86744:87619;%868-876  %Lowermost Edge from center (may be because of blinking) <br>
T.append([86743,87618]); <br>
<br>
<hr>
<br>