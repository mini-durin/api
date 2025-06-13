**Files**
./data.json: Basic information about characters.
./tr/: Localize file.


**Structure**
"name": String(3),
"country": String(2),
"element": String(1),
"wapon": String(1),
"ver": Int(2),
"model": String(1),
"vision": String(1),
"namechange": Int(1)


name = Character name

country = Affiliation country
  TR=Traveler
  MN=Mondstadt
  LY=Liyue
  IN=Inazuma
  SM=Sumeru
  FT=Fontaine
  NT=Natlan
  ND=Nod-Krai
  SN=Snezhnaya
  KR=Khaenri'ah
  FT=Fatui
  UN=Unknown

element = Element
  A=Anemo
  G=Geo
  P=Pyro
  H=Hydro
  E=Electro
  C=Cyro
  D=Dendro
  T=Traveler
  
weapon = Weapon Type
  S=Sword
  M=Claymore
  P=Polearm
  C=Catalyst
  B=Bow
  
ver = Major/minor updates are noted in 2 digits in hexadecimal numbers.
  ex.) A6=v10.6
  
model = 3D model type
  B=Boy
  M=Male
  L=Little Girl
  G=Girl
  F=Famale

vision = Vision type

rename = Numbers are assigned to characters whose names can be changed.
  X=Impossible
  0=Traveler
  1=Wanderer
  2=Little One
