gg.setVisible(false)
gg.sleep(200)
gg.alert("       🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷 \n       🇹🇷  ⚠️  HOŞGELDİNİZ  ⚠️ ️   🇹🇷\n       🇹🇷  👑 「AX」๛TEAM  👑   🇹🇷 \n       🇹🇷🇹🇷 👉SÜRÜM BETA👈🇹🇷🇹🇷 \n            🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷🇹🇷     ")

gg.sleep(250)
gg.toast("⚠️ SCRİPT YÜKLENİYOR ⚠️")
gg.sleep(400)
gg.setVisible(true)
PUBGMH = -1
function HOME() --Ana Menü
MENU = gg.choice({
           "••••••••••••••••••••••\n☠ •WH & CL• ☠ \n••••••••••••••••••••••  ",
           "••••••••••••••••••••••\n    ☠ •LOBİ• ☠\n••••••••••••••••••••••",
           "••••••••••••••••••••••\n   ☠ • OYUN• ☠\n•••••••••••••••••••••• ",
           "••••••••••••••••••••••\n    ☠ •BİLGİ• ☠\n•••••••••••••••••••••• ",
           "    ◄⎋ÇIKIŞ►"
}, nil, "               👉TELEGRAM : @axteampugb 👈 ")
    if MENU == nil then
  else
    if MENU == 1 then
      MN1()
    end
    if MENU == 2 then
     MN2()
    end
    if MENU == 3 then
     MN3()
    end
     if MENU == 4 then
    INFO()
    end
    if MENU == 5 then
      EXIT()
    end
  end
  PUBGMH = -1
end


function MN1() --Wh ve Ch
WC = gg.multiChoice({
           "SD 425",
           "SD 450",
           "SD 625",
           "SD 660",
           "SD 710",
		   "SD 845",
           "MENÜ"
}, nil, "🎯 ANTREMAN MODUNDA AÇINIZ 🎯")
  if WC == nil then
  else
    if WC [1] == true then
      WC1()
    end
    if WC [2] == true then
     WC2()
    end
    if WC [3] == true then
     WC3()
    end
    if WC [4] == true then
     WC4()
    end
    if WC [5] == true then
      WC5()
    end
	if WC [6] == true then
      WC6()
    end
    if WC [7] == true then
      HOME()
    end
  end
  PUBGMH = -1
end

function WC1() 
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('2.9427268e-44;2.0;3.0828566e-44;-1.0;3.2229865e-44;3.3631163e-44;3.643376e-44:97', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('3.1529215e-43;2.0F;3.1669345e-43F;3.1809475e-43:49', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.toast('Wallhack SD425 AÇILDI!')
end
 
function WC2()
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('135,215D;4,140D;3.7615819e-37;2::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('194D;3.7615819e-37;2;-1;1;-127::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('1.1202013e-19;1.1202017e-19;2::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.editAll('9999', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll('150', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('5.8013756e-42F;-5.5695588e-40F;2.0F::100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll('150', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('4.7961574e21;3.7615819e-37;2::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(30)
    gg.editAll('150', gg.TYPE_FLOAT)
    gg.toast('Wallhack SD450 AÇILDI!')
end
 
function WC3()
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('135,215D;4,140D;3.7615819e-37;2::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('194D;3.7615819e-37;2;-1;1;-127::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast('Wallhack SD625 AÇILDI!')
end

function WC4() 
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('4,140D;4.7408166e21;5.6896623e-29;4.7961574e21;3.7615819e-37;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(3)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('200,866D;0.24022650719;0.69314718246;0.00999999978;1;-1;2;-127:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(2)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('32,770D;0.01799999923;0.29907226562;-1;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(4)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('50,331,648D;0.01799999923;0.29907226562;0.5869140625;0.11401367188;-1;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(2)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('50,331,648D;0.04000854492;0.11999511719;-0.02749633789;-0.57177734375;-1;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('-1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('266,400D;0.24022650719;0.69314718246;0.00999999978;1;-1;-127;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('50,331,648D;0.04000854492;0.11999511719;-0.02749633789;-0.57177734375;-1;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(2)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('4,140D;4.7408149e21;-5.5695588e-40;4.814603e21;3.7615819e-37;2:', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.toast('Wallhack SD660 AÇILDI!')
end

function WC5()
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('274,677,779D;2.25000452995;2;1.6623054e-19', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(20)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('218D;3.7615819e-37;2;-1;1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('95D;2;9.2194229e-41', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(15)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('206D;3.7615819e-37;2;-1;1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('130', gg.TYPE_FLOAT)
    gg.toast('Wallhack SD710 AÇILDI!')
end

function WC6()
    gg.clearResults()
    gg.setRanges(gg.REGION_BAD)
    gg.searchNumber('95D;2;9.2194229e-41::100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(6)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('5.201992e21;2.25000452995;2;1.6623054e-19', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(4)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.searchNumber('2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll('120', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast('Wallhack SD845 AÇILDI!')
end



--------STEP[1] Lobby👇--------

function MN2() --Menü lobi
ML = gg.multiChoice({
           "SEKMEME",
           "SEKMEME (TİTREMESİZ)",
           "OTO NİŞAN 100M",
           "LOG TEMİZLEME",
           "YAPIMDA",
           "BACK"
}, nil, "️ NE MUTLU TÜRKÜM DİYENE ️")
  if ML == nil then
  else
    if ML [1] == true then
      ML1()
    end
    if ML [2] == true then
     ML2()
    end
    if ML [3] == true then
     ML3()
    end
    if ML [4] == true then
     ML4()
    end
    if ML [5] == true then
      ML5()
    end
    if ML [6] == true then
      HOME()
    end
  end
  PUBGMH = -1
end

function ML1() 
  gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("-1903895931231645695", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("-1903895931231645695", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("2A0", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("-1903895931231645695", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1401)
  gg.editAll("-1903895931231645696", gg.TYPE_QWORD)
  gg.clearResults()
  gg.toast("SEKMEME AÇILDI")
  end
 
function ML2()
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-2.786982e28;-3.7444097e28;-1.1368837e-13::", 16, false, 536870912, 0, -1)
gg.searchNumber("-3.7444097e28", 16, false, 536870912, 0, -1)
gg.getResults(1)
gg.editAll("0", 16)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", 16, false, 536870912, 0, -1)
gg.searchNumber("-1.1144502e28", 16, false, 536870912, 0, -1)
gg.getResults(1)
gg.editAll("0", 16)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", 16, false, 536870912, 0, -1)
gg.searchNumber("-1.1144502e28", 16, false, 536870912, 0, -1)
gg.getResults(1)
gg.editAll("0", 16)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1,348,759,109;1953067887;1,634,692,166;1,920,287,604::28", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1634692166", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("1634692266", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("%100 SEKMEME AÇILDI!")
gg.clearResults()
end
 
function ML3()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("OTO NİŞAN 100M AÇILDI")
end

function ML4() 
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/cache")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/tbslog")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/ca-bundle.pem")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/cacheFile.txt")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/login-identifier.txt")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/vmpcloudconfig.json")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/ProgramBinaryCache")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_temp")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_res.eifs")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/1375135419_47_0.13.0.11098_20190617165748_1981158817_cures.ifs.res")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/UpdateInfo")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/RoleInfo")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Pandora")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/PufferTmpDir")
os.remove("/data/data/com.tencent.ig/app_appcache")
os.remove("/data/data/com.tencent.ig/app_bugly")
os.remove("/data/data/com.tencent.ig/app_crashrecord")
os.remove("/data/data/com.tencent.ig/cache")
os.remove("/data/data/com.tencent.ig/code_cache")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/cache")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/tbslog")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/ca-bundle.pem")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/cacheFile.txt")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/login-identifier.txt")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/vmpcloudconfig.json")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/ProgramBinaryCache")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_temp")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_res.eifs")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/1375135419_47_0.13.0.11098_20190617165748_1981158817_cures.ifs.res")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/UpdateInfo")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/RoleInfo")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Pandora")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/PufferTmpDir")
os.remove("/data/data/com.pubg.krmobile/app_appcache")
os.remove("/data/data/com.pubg.krmobile/app_bugly")
os.remove("/data/data/com.pubg.krmobile/app_crashrecord")
os.remove("/data/data/com.pubg.krmobile/cache")
os.remove("/data/data/com.pubg.krmobile/code_cache")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/cache")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/tbslog")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/ca-bundle.pem")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/cacheFile.txt")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/login-identifier.txt")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/vmpcloudconfig.json")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/ProgramBinaryCache")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_temp")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_res.eifs")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/1375135419_47_0.13.0.11098_20190617165748_1981158817_cures.ifs.res")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/UpdateInfo")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/RoleInfo")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Pandora")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/PufferTmpDir")
os.remove("/data/data/com.vng.pubgmobile/app_appcache")
os.remove("/data/data/com.vng.pubgmobile/app_bugly")
os.remove("/data/data/com.vng.pubgmobile/app_crashrecord")
os.remove("/data/data/com.vng.pubgmobile/cache")
os.remove("/data/data/com.vng.pubgmobile/code_cache")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/cache")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/tbslog")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/ca-bundle.pem")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/cacheFile.txt")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/login-identifier.txt")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/vmpcloudconfig.json")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/ProgramBinaryCache")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_temp")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/puffer_res.eifs")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Paks/1375135419_47_0.13.0.11098_20190617165748_1981158817_cures.ifs.res")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/UpdateInfo")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/RoleInfo")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Pandora")
os.remove("/storage/emulated/0/Android/data/com.rekoo.pubgm/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/PufferTmpDir")
os.remove("/data/data/com.rekoo.pubgm/app_appcache")
os.remove("/data/data/com.rekoo.pubgm/app_bugly")
os.remove("/data/data/com.rekoo.pubgm/app_crashrecord")
os.remove("/data/data/com.rekoo.pubgm/cache")
os.remove("/data/data/com.rekoo.pubgm/code_cache")
gg.toast("LOG TEMİZLENDİ")
end

function ML5()
    gg.toast('YAPIMDA')
end



--------STEP[4] Game👇--------

function MN3() --Menü oyun
MG = gg.multiChoice({
           "KAFADAN VURMA %100",
           "ANTEN",
           "ANTEN KAMUFLAJ",
           "JİPİ HIZLANDIR",
           "OTUR DÜRBÜN AÇ",
		   "GERİDEN GÖRÜŞ",
		   "GÖRÜNMEZLİK (15 sn)",
		   "HIZLI İNME PARAŞÜT (ADA)",
           "BACK",
}, nil, " BİR ÖLÜR BİN DİRİLİRİZ")
  if MG == nil then
  else
    if MG [1] == true then
      MG1()
    end
    if MG [2] == true then
     MG2()
    end
    if MG [3] == true then
     MG3()
    end
    if MG [4] == true then
     MG4()
    end
    if MG [5] == true then
      MG5()
    end
    if MG [6] == true then
      MG6()
    end
    if MG [7] == true then
      MG7()
    end
    if MG [8] == true then
      MG8()
    end
    if MG [9] == true then
      HOME()
    end
  end
  PUBGMH = -1
end

function MG1() 
  gg.setRanges(131072)
  gg.searchNumber("-88.66608428955;26", 16, false, 536870912, 0, -1)
  gg.searchNumber("26", 16, false, 536870912, 0, -1)
  gg.getResults(2)
  gg.editAll("-466", 16)
  gg.clearResults()
  gg.searchNumber("-88.73961639404;28", 16, false, 536870912, 0, -1)
  gg.searchNumber("28", 16, false, 536870912, 0, -1)
  gg.getResults(2)
  gg.editAll("-568", 16)
  gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("9.201618;30.5;25", 16, false, 536870912, 0, -1)
  gg.searchNumber("30.5;25", 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll("280", 16)
  gg.clearResults()
  gg.toast("KAFADAN VURMA %100 AÇILDI")
end
 
function MG2()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('88.50576019287F;87.27782440186F;-100.91194152832F;1F::13', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('88.50576019287F;87.27782440186F;1F', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(6)
    gg.editAll('1.96875;1.96875;999;1.96875;1.96875;999', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast('Anten AÇILDI ✔')
	gg.clearResults()
end
 
function MG3()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.98900693655~0.98900723457;0.14786802232~0.14786840975;1.1920926e-7::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResultCount()
  gg.searchNumber("0.98900693655~0.98900723457", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("16000", gg.TYPE_FLOAT)
  gg.toast("ANTEN KAMUFLAJ AÇILDI")
end

function MG4() 
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('0.76000005007;0.96078431606;1;0.74509805441::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('0.74509805441', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(9999)
    gg.editAll('100', gg.TYPE_FLOAT)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('50;5;0.01', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('0.01', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(280)
    gg.editAll('-0.23', gg.TYPE_FLOAT)
    gg.toast('TÜM ARABALAR HIZLANDIRILDI ✔')
	gg.clearResults()
end

function MG5()
      gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.sleep(140)
  gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.sleep(140)
  gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1401)
  gg.editAll("-4767057191527907328", gg.TYPE_QWORD)
  gg.clearResults()
  gg.toast("OTUR DÜRBÜN AÇ AÇILDI")
end

function MG6()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('2.8025969e-45;220;25;178;15;100', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('220', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll('440', gg.TYPE_FLOAT)
    gg.toast('GERİDEN GÖRÜŞ AÇILDI !')
	gg.clearResults()
end

function MG7()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("10000;20000::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("10000", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(9999)
  gg.editAll("500", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("GÖRÜNMEZLİK AÇILDI 15sn VAR")
  gg.sleep(1000)
  gg.toast("15")
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.toast("10")
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.toast("5")
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.sleep(1000)
  gg.toast("GÖRÜNMEZLİK KAPANIYOR")
  gg.sleep(500)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("500;20000::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("500", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(9999)
  gg.editAll("10000", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("ARTIK GÖRÜNÜRSÜN")

end

function MG8()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("200;200;1;1::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResultCount()
  gg.getResults(25)
  gg.editAll("2400", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("HIZLI PARAŞÜT AÇILDI")
end

function INFO()
gg.alert(os.date("    ----------HİLELER HAKINDA BİLGİ----------\n \n                          ☠ •LOBİ• ☠\n• SEKMEME\nSilahınızın sekmemesini sağlar.\n• SEKMEME(TİTREŞİMSİZ)\nSilahınızın titremeden sekmemesini sağlar."))
gg.setVisible(true)
end

function EXIT()
print("⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️       \n⚠️ TELEGRAM ➡ @axteampugb  ⚠️  \n  ⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️ ")
  gg.skipRestoreState()
  gg.setVisible(true)
  os.exit()
end
while true do
  if gg.isVisible(true) then
    PUBGMH = 1
    gg.setVisible(false)
  end
  if PUBGMH == 1 then
    HOME()
  end
end
