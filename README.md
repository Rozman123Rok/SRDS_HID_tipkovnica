# Uporaba naprave HID

Za razvojno ploščico napišite sistemsko programsko opremo, ki bo demonstrirala uporabo protokola USB HID za tipkovnico.

Implementacija naj upošteva naslednje zahteve:

## konfiguracija GPIO priklopov:
- priklop PA0 (modri gumb) kot vhod

## konfiguracija naprave HID:
- opisni niz produkta (PRODUCT_STRING) naj bo "KeyboardGhost"

## demo tipkovnica preprosto:
- ob prvem (lihem) pritisku na gumb natipkajte : 23390
- časovni zamik med pošiljanjem posameznega znaka naj bo 245 ms

## demo tipkovnica napredno:
- ob drugem (sodem) pritisku na gumb natipkajte ASCII tabelo od 32 do 126 znaka
- časovni zamik med pošiljanjem posameznega znaka naj bo 245 ms

Prevedeno sistemsko programsko opremo oddajte v formatu .hex.

V arhivu naloga.zip oddajte naslednjo strukturo:

mapa "Core" (iz korenskega imenika projekta z vsemi podmapami in datotekami)
mapa "USB_DEVICE" (iz korenskega imenika projekta z vsemi podmapami in datotekami)
prevedena sistemska programska oprema (v formatu .hex)