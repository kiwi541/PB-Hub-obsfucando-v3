--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v89=0;while true do if (v89==0) then v19=v0(v3(v30,1,1));return "";end end else local v90=0;local v91;while true do if (v90==0) then v91=v2(v0(v30,16));if v19 then local v121=v5(v91,v19);v19=nil;return v121;else return v91;end break;end end end end);local function v20(v31,v32,v33) if v33 then local v92=0 -(877 -(282 + 595)) ;local v93;while true do if (v92==(0 -(1637 -(1523 + 114)))) then v93=(v31/(2^(v32-1)))%((3 -1)^(((v33-(2 -1)) -(v32-(620 -(555 + 58 + 6)))) + 1)) ;return v93-(v93%(932 -(857 + 74))) ;end end else local v94=(570 -(367 + 201))^(v32-(928 -(214 + 713))) ;return (((v31%(v94 + v94))>=v94) and (1 + 0)) or (0 + 0) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=0 -0 ;local v36;local v37;while true do if (v35==(1 -0)) then return (v37 * 256) + v36 ;end if (v35==(117 -(32 + 85))) then v36,v37=v1(v16,v18,v18 + ((2544 -1477) -(68 + 997)) );v18=v18 + 1 + 1 ;v35=1271 -((417 -191) + 1044) ;end end end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + 3 );v18=v18 + (7 -(7 -4)) ;return (v41 * (16777566 -(87 + 263))) + (v40 * ((48331 + 17385) -(67 + (449 -336)))) + (v39 * (188 + 68)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=953 -(802 + 150) ;local v45=(v20(v43,2 -1 ,(114 -78) -16 ) * ((2 + 0)^(1518 -(998 + 488)))) + v42 ;local v46=v20(v43,1018 -(915 + 82) ,87 -56 );local v47=((v20(v43,19 + 6 + 7 )==(1 -0)) and  -1) or (1188 -((1890 -821) + 118)) ;if (v46==(0 -0)) then if (v45==(0 -0)) then return v47 * (0 + 0) ;else local v113=0;while true do if (v113==(0 -0)) then v46=1;v44=0;break;end end end elseif (v46==(2031 + 16)) then return ((v45==(791 -(368 + 423))) and (v47 * ((3 -2)/(18 -(10 + 3 + 5))))) or (v47 * NaN) ;end return v8(v47,v46-(3934 -2911) ) * (v44 + (v45/((440 -(145 + 293))^(494 -(416 + 26))))) ;end local function v25(v48) local v49;if  not v48 then v48=v23();if (v48==(0 + 0)) then return "";end end v49=v3(v16,v18,(v18 + v48) -(773 -(201 + 571)) );v18=v18 + v48 ;local v50={};for v66=1139 -(116 + 1022) , #v49 do v50[v66]=v2(v1(v3(v49,v66,v66)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return function(v95,v96,v97,v98,v99,v100,v101,v102,v103) local v104=(function() return 0;end)();local v95=(function() return;end)();local v96=(function() return;end)();while true do local v112=(function() return 0 + 0 ;end)();while true do if (v112==0) then if (v104==1) then while true do if (v95==(935 -(39 + 896))) then v96=(function() return v97();end)();if (v98(v96, #"[", #"}")==(0 -0)) then local v151=(function() return 0;end)();local v152=(function() return;end)();local v153=(function() return;end)();local v154=(function() return;end)();while true do if (v151~=0) then else v152=(function() return v98(v96,2 -0 , #"xnx");end)();v153=(function() return v98(v96, #"0836",6);end)();v151=(function() return 2 -1 ;end)();end if (v151==1) then local v176=(function() return 0;end)();while true do if ((0 + 0)==v176) then v154=(function() return {v99(),v99(),nil,nil};end)();if (v152==(396 -(115 + 281))) then local v183=(function() return 0;end)();local v184=(function() return;end)();while true do if (v183~=(0 -0)) then else v184=(function() return 0;end)();while true do if ((0 + 0)==v184) then v154[ #"xnx"]=(function() return v99();end)();v154[ #".dev"]=(function() return v99();end)();break;end end break;end end elseif (v152== #"}") then v154[ #"19("]=(function() return v100();end)();elseif (v152==2) then v154[ #"91("]=(function() return v100() -((4 -2)^(58 -42)) ;end)();elseif (v152~= #"asd") then else local v189=(function() return 0;end)();local v190=(function() return;end)();while true do if (v189~=(867 -(550 + 317))) then else v190=(function() return 0;end)();while true do if (v190==0) then v154[ #"19("]=(function() return v100() -((2 -0)^(22 -6)) ;end)();v154[ #".dev"]=(function() return v99();end)();break;end end break;end end end v176=(function() return 2 -1 ;end)();end if (v176~=(286 -(134 + 151))) then else v151=(function() return 1667 -(970 + 695) ;end)();break;end end end if (v151==(5 -2)) then if (v98(v153, #"xxx", #"-19")~= #"\\") then else v154[ #"asd1"]=(function() return v101[v154[ #".dev"]];end)();end v102[v103]=(function() return v154;end)();break;end if (v151~=(1992 -(582 + 1408))) then else if (v98(v153, #",", #"|")~= #"[") then else v154[2]=(function() return v101[v154[6 -4 ]];end)();end if (v98(v153,2,2 -0 )== #"!") then v154[ #"91("]=(function() return v101[v154[ #"91("]];end)();end v151=(function() return 3;end)();end end end break;end end return v95,v96,v97,v98,v99,v100,v101,v102,v103;end if (v104~=0) then else local v124=(function() return 0;end)();while true do if ((0 -0)==v124) then v95=(function() return 0;end)();v96=(function() return nil;end)();v124=(function() return 1;end)();end if (1~=v124) then else v104=(function() return 1;end)();break;end end end break;end end end end;end)();local v52=(function() return function(v105,v106,v107) local v108=(function() return 0;end)();local v109=(function() return;end)();while true do if (v108~=(1824 -(1195 + 629))) then else v109=(function() return 0;end)();while true do if (v109==0) then local v125=(function() return 0;end)();while true do if (v125==(0 -0)) then v105[v106-#"," ]=(function() return v107();end)();return v105,v106,v107;end end end end break;end end end;end)();local v53=(function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {v53,v54,nil,v55};end)();local v57=(function() return v23();end)();local v58=(function() return {};end)();for v68= #".",v57 do local v69=(function() return 0;end)();local v70=(function() return;end)();local v71=(function() return;end)();local v72=(function() return;end)();while true do if (v69~=1) then else v72=(function() return nil;end)();while true do if (v70==1) then if (v71== #"~") then v72=(function() return v21()~=0 ;end)();elseif (v71==2) then v72=(function() return v24();end)();elseif (v71== #"asd") then v72=(function() return v25();end)();end v58[v68]=(function() return v72;end)();break;end if ((241 -(187 + 54))==v70) then local v123=(function() return 780 -(162 + 618) ;end)();while true do if (v123~=0) then else v71=(function() return v21();end)();v72=(function() return nil;end)();v123=(function() return 1;end)();end if (v123~=1) then else v70=(function() return 1 + 0 ;end)();break;end end end end break;end if (v69==0) then local v114=(function() return 0;end)();while true do if (v114~=1) then else v69=(function() return 1;end)();break;end if (v114~=(0 + 0)) then else v70=(function() return 0;end)();v71=(function() return nil;end)();v114=(function() return 1;end)();end end end end end v56[ #"xnx"]=(function() return v21();end)();for v73= #"|",v23() do FlatIdent_39B0,Descriptor,v21,v20,v22,v23,v58,v53,v73=(function() return v51(FlatIdent_39B0,Descriptor,v21,v20,v22,v23,v58,v53,v73);end)();end for v74= #"~",v23() do v54,v74,v28=(function() return v52(v54,v74,v28);end)();end return v56;end local function v29(v60,v61,v62) local v63=v60[1 -0 ];local v64=v60[2 -0 ];local v65=v60[1 + 2 ];return function(...) local v75=v63;local v76=v64;local v77=v65;local v78=v27;local v79=585 -(57 + 178 + 349) ;local v80= -(1428 -(41 + 1386));local v81={};local v82={...};local v83=v12("#",...) -(1637 -(1373 + 263)) ;local v84={};local v85={};for v110=0,v83 do if ((2253==2253) and (v110>=v77)) then v81[v110-v77 ]=v82[v110 + (1001 -((1060 -609) + 549)) ];else v85[v110]=v82[v110 + 1 + (1202 -(373 + 829)) ];end end local v86=(v83-v77) + (1 -0) ;local v87;local v88;while true do local v111=0 -0 ;while true do if ((452==452) and (v111==(166 -(122 + 44)))) then v87=v75[v79];v88=v87[1385 -(746 + 638) ];v111=1 + 0 ;end if ((v111==(1 -0)) or (4557<2087)) then if (v88<=(344 -(218 + 123))) then if (v88<=(1 + (731 -(476 + 255)))) then if (v88>(1581 -((2665 -(369 + 761)) + 27 + 19))) then do return;end else local v127=v87[3 -1 ];local v128=v85[v87[68 -(30 + 35) ]];v85[v127 + 1 + 0 ]=v128;v85[v127]=v128[v87[(2290 -1029) -(1043 + 214) ]];end elseif (v88>(7 -5)) then local v132=v87[1 + 1 ];v85[v132]=v85[v132](v13(v85,v132 + 1 ,v80));else v85[v87[(2300 -1086) -(323 + 889) ]]();end elseif (v88<=(565 -(306 + (492 -(64 + 174))))) then if (v88>(1 + 0 + 3)) then local v134=0 -0 ;local v135;local v136;local v137;local v138;local v139;while true do if ((3874==3874) and (v134==(1 + 1))) then v85[v139 + (1468 -(899 + 568)) ]=v138;v85[v139]=v138[v87[3 + (1 -0) ]];v79=v79 + (3 -2) ;v87=v75[v79];v85[v87[4 -2 ]]=v87[606 -(268 + 335) ];v79=v79 + 1 + 0 ;v134=293 -(60 + 230) ;end if ((573 -(426 + 146))==v134) then v87=v75[v79];v85[v87[1 + 1 ]]=v62[v87[1459 -(282 + 1174) ]];v79=v79 + (812 -(569 + (578 -(144 + 192)))) ;v87=v75[v79];v139=v87[5 -3 ];v138=v85[v87[1 + 2 ]];v134=1026 -(706 + 318) ;end if (v134==(1251 -(721 + 530))) then v135=nil;v136,v137=nil;v138=nil;v139=nil;v85[v87[1273 -(945 + 326) ]]=v62[v87[7 -(220 -(42 + 174)) ]];v79=v79 + 1 + 0 ;v134=701 -(271 + 429) ;end if (v134==(5 + 0)) then v85[v87[7 -5 ]]();v79=v79 + (1501 -(1408 + 92)) ;v87=v75[v79];do return;end break;end if ((v134==(1089 -(461 + 470 + 155))) or (1938>4935)) then v87=v75[v79];v139=v87[1290 -(993 + 295) ];v136,v137=v78(v85[v139](v13(v85,v139 + 1 + 0 ,v87[3 + 0 ])));v80=(v137 + v139) -(1172 -(418 + 753)) ;v135=0 + 0 ;for v174=v139,v80 do local v175=0 + 0 ;while true do if (v175==(0 -0)) then v135=v135 + 1 + 0 ;v85[v174]=v136[v135];break;end end end v134=2 + 2 ;end if (v134==(3 + 1 + 0)) then v79=v79 + 1 + 0 ;v87=v75[v79];v139=v87[1 + 1 ];v85[v139]=v85[v139](v13(v85,v139 + (530 -(406 + 123)) ,v80));v79=v79 + (1770 -(1749 + 20)) ;v87=v75[v79];v134=2 + 3 ;end end else v85[v87[1324 -(1249 + 73) ]]=v87[2 + (1505 -(363 + 1141)) ];end elseif (v88==(1151 -((2046 -(1183 + 397)) + 679))) then local v142=v87[9 -7 ];local v143,v144=v78(v85[v142](v13(v85,v142 + (2 -1) ,v87[8 -5 ])));v80=(v144 + v142) -(1901 -(106 + 1794)) ;local v145=(0 -0) + 0 ;for v148=v142,v80 do v145=v145 + 1 + 0 ;v85[v148]=v143[v145];end else v85[v87[5 -(3 + 0) ]]=v62[v87[3 + 0 + 0 ]];end v79=v79 + 1 ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403513Q00682Q7470733A2Q2F7261772E67697468756275736572636F6E74656E742E636F6D2F6B6977693534312F50422D6C6F61647472696E672D2F726566732F68656164732F6D61696E2F524541444D452E6D6400083Q0012053Q00013Q00122Q000100023Q00202Q00010001000300122Q000300046Q000100039Q0000026Q000100016Q00017Q00",v9(),...);
