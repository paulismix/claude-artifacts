# 01 ⚡ Kalkulačka ceny cesty elektromobilem

Jednoduchá webová kalkulačka, která spočítá náklady na elektřinu za cestu elektromobilem. Stačí zadat spotřebu, cenu elektřiny a vzdálenost — výsledek se počítá průběžně.

🔗 **Demo:** https://claude.ai/public/artifacts/7f96b26d-9534-42bc-a78d-0f757ca4efb3

## ✨ Funkce

- Výpočet ceny cesty na základě spotřeby, ceny elektřiny a vzdálenosti
- Průběžný přepočet při psaní (není potřeba nic odesílat)
- Zobrazení celkové spotřeby v kWh i ceny za 1 km
- Automatický výpočet ceny zpáteční cesty
- Podpora desetinné čárky i tečky (`6,5` i `6.5`)
- Responzivní design — funguje na mobilu i na počítači

## 🧮 Jak se počítá

```
celková spotřeba (kWh) = spotřeba (kWh/100 km) × vzdálenost (km) ÷ 100
cena cesty (Kč)        = celková spotřeba (kWh) × cena elektřiny (Kč/kWh)
```

**Příklad:** spotřeba 16 kWh/100 km, cena 6,50 Kč/kWh, vzdálenost 120 km
→ 19,2 kWh × 6,50 Kč = **124,80 Kč**

> ⚠️ Výpočet je orientační. Nezohledňuje ztráty při nabíjení ani spotřebu topení či klimatizace.
