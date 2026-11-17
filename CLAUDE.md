# Repo: urologo-pedregal-landing-octubre-2026 — ESTE REPO ES **Pedregal real**

> **ANTES DE EDITAR**: lee esto completo. Este repo sirve a `https://urologospedregal.com` — es la **Clínica de Próstata en Pedregal**. Lo que edites aquí lo ve el doctor y los pacientes de Pedregal.

---

## Mapa autoritativo (confirmado por el cliente 2026-11-17)

| Repo GitHub | Local path | Dominio Vercel | Sede |
|---|---|---|---|
| `fercho159-aq/urologo-pedregal-landing-octubre-2026` | `C:\Users\alexi\Desktop\pedregal-real` (ESTE) | `urologospedregal.com` | **Pedregal real** (Clínica de Próstata) |
| `fercho159-aq/urologo-pedregal-landing` | `C:\Users\alexi\Desktop\urologoPedregal` | `www.cdmxurologo.com` | **Cd. Deportes / Patriotismo** |

**Los nombres de los repos engañan.** El que NO tiene `-octubre-2026` NO es Pedregal: es Cd. Deportes.

---

## Las dos sedes

| Sede | Nombre comercial | Campaña Google Ads |
|---|---|---|
| **Pedregal** | Clínica de Próstata en Pedregal CDMX | "urólogo Pedregal" |
| **Cd. Deportes / Patriotismo** | Centro Urológico de Alta Especialidad (CDMX) | "urólogo CDMX" |

---

## Regla de edición — leer antes de tocar NADA

### El usuario dice "Pedregal", "clínica de próstata", "cirugías (Pedregal)", "cálculos renales (Pedregal)", "urologospedregal.com"
→ ✅ Editar aquí. Es el repo correcto.

### El usuario dice "Cd. Deportes", "CDMX", "Patriotismo", "cdmxurologo.com"
→ ❌ NO editar aquí. Ir al otro repo: `C:\Users\alexi\Desktop\urologoPedregal`.

---

## Estructura del repo

```
C:\Users\alexi\Desktop\pedregal-real\
├── vercel.json                       ← rewritea `/` → `/urologo-pedregal/index.html`
├── urologo-pedregal/
│   ├── index.html                    ← landing principal Pedregal (Check Up, Clínica)
│   ├── cirugias/index.html           ← cirugía de próstata
│   ├── calculos-renales/index.html   ← cálculos renales
│   ├── favicon.ico, favicon-180.png, logo.png, img-hero.jpg
```

---

## Verificación después de push

Cambios aquí se reflejan en `https://urologospedregal.com/`. Vercel deploya en < 2 min.

Comando rápido:
```bash
curl -s "https://urologospedregal.com/?v=$(date +%s)" | grep "Check Up Próstata Básico" -A 5
```

---

## Historial útil

- Commit `9ab2b73` (antes de hoy) — gtag a `AW-16973737252`.
- **2026-11-17:** aplicadas 5 correcciones del doctor:
  - Quitado "Antígeno prostático (PSA)" del Check Up Básico ($900). Sigue en el Completo.
  - Quitado "Planes de financiamiento accesibles" en `cirugias/` y `calculos-renales/` (el doctor no da financiamiento directo).
  - FAQs reescritas: en vez de "ofrecemos planes de financiamiento y pago a meses sin intereses" ahora dicen "aceptamos pago a meses sin intereses con tarjetas de crédito participantes" (que es lo real: via bancos, no financiamiento directo).
