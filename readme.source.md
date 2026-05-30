```aura width=800 height=240
<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: '#06020a', borderRadius: 20, padding: 30, fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden', border: '1px solid rgba(251,38,65,0.15)' }}>
  <style>
    {`
      @keyframes ho-a { 0%, 100% { transform: translate(0,0); opacity: 0.7; } 50% { transform: translate(28px,-20px); opacity: 1; } }
      @keyframes ho-b { 0%, 100% { transform: translate(0,0); opacity: 0.55; } 50% { transform: translate(-22px,16px); opacity: 0.85; } }
      @keyframes ho-c { 0%, 100% { transform: translate(0,0); opacity: 0.4; } 50% { transform: translate(14px,-24px); opacity: 0.65; } }
      @keyframes hr-blink { 0%, 100% { opacity: 0.07; } 50% { opacity: 0.2; } }
      @keyframes hd-spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
      @keyframes hpill { 0%, 100% { opacity: 0.7; } 50% { opacity: 1; } }
      #ho1 { animation: ho-a 9s ease-in-out infinite; }
      #ho2 { animation: ho-b 11s ease-in-out infinite 1s; }
      #ho3 { animation: ho-a 8s ease-in-out infinite 2s; }
      #ho4 { animation: ho-b 13s ease-in-out infinite 0.5s; }
      #ho5 { animation: ho-c 7s ease-in-out infinite 1.5s; }
      #hr1 { animation: hr-blink 8s ease-in-out infinite; }
      #hr2 { animation: hr-blink 8s ease-in-out infinite 1.6s; }
      #hr3 { animation: hr-blink 10s ease-in-out infinite 3.2s; }
      #hdot { animation: hd-spin 22s linear infinite; }
      #hpill { animation: hpill 3s ease-in-out infinite; }
    `}
  </style>
  <svg width="800" height="240" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="hg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(251,38,65,0.55)" />
        <stop offset="100%" stopColor="rgba(251,38,65,0)" />
      </radialGradient>
      <radialGradient id="hg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(254,149,105,0.5)" />
        <stop offset="100%" stopColor="rgba(254,149,105,0)" />
      </radialGradient>
      <radialGradient id="hg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(253,177,73,0.35)" />
        <stop offset="100%" stopColor="rgba(253,177,73,0)" />
      </radialGradient>
      <radialGradient id="hg4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(251,38,65,0.28)" />
        <stop offset="100%" stopColor="rgba(251,38,65,0)" />
      </radialGradient>
      <radialGradient id="hg5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(254,149,105,0.3)" />
        <stop offset="100%" stopColor="rgba(254,149,105,0)" />
      </radialGradient>
    </defs>
    <ellipse id="ho1" cx="100" cy="200" rx="240" ry="180" fill="url(#hg1)" />
    <ellipse id="ho2" cx="720" cy="60"  rx="220" ry="180" fill="url(#hg2)" />
    <ellipse id="ho3" cx="640" cy="220" rx="200" ry="155" fill="url(#hg3)" />
    <ellipse id="ho4" cx="200" cy="45"  rx="185" ry="140" fill="url(#hg4)" />
    <ellipse id="ho5" cx="400" cy="230" rx="160" ry="120" fill="url(#hg5)" />
    <circle id="hr1" cx="400" cy="150" r="55"  fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.6" />
    <circle id="hr2" cx="400" cy="150" r="95"  fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.6" />
    <circle id="hr3" cx="400" cy="150" r="145" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.6" />
    <g id="hdot"><circle cx="400" cy="95" r="2.5" fill="rgba(251,38,65,0.7)" /></g>
  </svg>
  <div id="hpill" style={{ display: 'flex', alignItems: 'center', gap: 7, padding: '5px 14px', borderRadius: 9999, background: 'rgba(251,38,65,0.12)', border: '1px solid rgba(251,38,65,0.28)', color: '#fb2641', fontSize: 11, fontWeight: 500, letterSpacing: '0.06em', textTransform: 'uppercase', marginBottom: 22 }}>
    <span style={{ width: 6, height: 6, borderRadius: '50%', background: '#fb2641', display: 'flex' }} />
    <span>Ouvert aux alternances · Data / AI · Sept. 2026</span>
  </div>
  <div style={{ display: 'flex', alignItems: 'center', gap: 0, lineHeight: 1 }}>
    <span style={{ fontSize: 62, fontWeight: 900, color: '#ffffff', letterSpacing: '-3px' }}>Terrel&nbsp;</span>
    <span style={{ fontSize: 62, fontWeight: 900, letterSpacing: '-3px', background: 'linear-gradient(to right, #fb2641, #fe9569, #fdb149)', WebkitBackgroundClip: 'text', backgroundClip: 'text', color: 'transparent' }}>NUENTSA</span>
  </div>
  <span style={{ fontSize: 14, color: 'rgba(255,255,255,0.38)', marginTop: 14, letterSpacing: '0.12em', textTransform: 'uppercase', fontWeight: 300 }}>Concevoir · Coder · Déployer</span>
</div>
```

```aura width=800 height=210
<div style={{ display: 'flex', flexDirection: 'row', gap: 14, width: '100%', height: '100%', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes ab-a { 0%, 100% { transform: translate(0,0); opacity: 0.6; } 50% { transform: translate(18px,-14px); opacity: 0.9; } }
    @keyframes ab-b { 0%, 100% { transform: translate(0,0); opacity: 0.5; } 50% { transform: translate(-14px,10px); opacity: 0.75; } }
    @keyframes ab-ring { 0%, 100% { opacity: 0.06; } 50% { opacity: 0.18; } }
    @keyframes ab-cur { 0%, 49% { opacity: 1; } 50%, 99% { opacity: 0; } }
    #abo1 { animation: ab-a 8s ease-in-out infinite; }
    #abo2 { animation: ab-b 10s ease-in-out infinite 1s; }
    #abo3 { animation: ab-a 7s ease-in-out infinite 2s; }
    #abr1 { animation: ab-ring 7s ease-in-out infinite; }
    #abr2 { animation: ab-ring 7s ease-in-out infinite 2s; }
    #ab-cursor { animation: ab-cur 1.1s step-end infinite; }
  `}</style>
  <div style={{ position: 'relative', display: 'flex', flex: 1, height: '100%', background: '#06020a', borderRadius: 16, overflow: 'hidden', border: '1px solid rgba(251,38,65,0.12)' }}>
    <svg width="100%" height="210" style={{ position: 'absolute', top: 0, left: 0 }}>
      <defs>
        <radialGradient id="abg1" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="rgba(251,38,65,0.55)" />
          <stop offset="100%" stopColor="rgba(251,38,65,0)" />
        </radialGradient>
        <radialGradient id="abg2" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="rgba(253,177,73,0.4)" />
          <stop offset="100%" stopColor="rgba(253,177,73,0)" />
        </radialGradient>
        <radialGradient id="abg3" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="rgba(254,149,105,0.35)" />
          <stop offset="100%" stopColor="rgba(254,149,105,0)" />
        </radialGradient>
      </defs>
      <ellipse id="abo1" cx="40"  cy="175" rx="120" ry="100" fill="url(#abg1)" />
      <ellipse id="abo2" cx="330" cy="35"  rx="110" ry="95"  fill="url(#abg2)" />
      <ellipse id="abo3" cx="260" cy="195" rx="95"  ry="85"  fill="url(#abg3)" />
      <circle id="abr1" cx="155" cy="105" r="36" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.6" />
      <circle id="abr2" cx="155" cy="105" r="62" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.6" />
    </svg>
    <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '0 28px' }}>
      <span style={{ fontSize: 10, color: 'rgba(251,38,65,0.7)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 10, fontWeight: 500 }}>À propos</span>
      <span style={{ fontSize: 20, fontWeight: 700, color: '#ffffff', lineHeight: 1.35 }}>Profil hybride</span>
      <span style={{ fontSize: 20, fontWeight: 700, color: '#ffffff', lineHeight: 1.35 }}>Mathématiques & IA.</span>
      <div style={{ display: 'flex', alignItems: 'center', marginTop: 12 }}>
        <span style={{ fontSize: 12, color: 'rgba(255,255,255,0.4)', fontFamily: 'monospace' }}>{'> EDF · M1 MIAGE Dauphine'}</span>
        <span id="ab-cursor" style={{ fontSize: 12, color: 'rgba(251,38,65,0.8)', fontFamily: 'monospace', marginLeft: 1 }}>_</span>
      </div>
    </div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: 14, width: 210, flexShrink: 0 }}>
    <div style={{ position: 'relative', display: 'flex', flex: 1, background: '#06020a', borderRadius: 14, overflow: 'hidden', alignItems: 'center', justifyContent: 'center', border: '1px solid rgba(251,38,65,0.12)' }}>
      <svg width="210" height="92" style={{ position: 'absolute', top: 0, left: 0 }}>
        <defs>
          <radialGradient id="sm1" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(251,38,65,0.4)" />
            <stop offset="100%" stopColor="rgba(251,38,65,0)" />
          </radialGradient>
        </defs>
        <ellipse cx="180" cy="80" rx="90" ry="70" fill="url(#sm1)" />
      </svg>
      <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
        <span style={{ fontSize: 28, fontWeight: 900, color: '#fb2641' }}>🏀</span>
        <span style={{ fontSize: 10, color: 'rgba(255,255,255,0.35)', letterSpacing: 3, textTransform: 'uppercase', marginTop: 4 }}>NBA fan</span>
      </div>
    </div>
    <div style={{ position: 'relative', display: 'flex', flex: 1, background: '#06020a', borderRadius: 14, overflow: 'hidden', alignItems: 'center', justifyContent: 'center', border: '1px solid rgba(253,177,73,0.12)' }}>
      <svg width="210" height="92" style={{ position: 'absolute', top: 0, left: 0 }}>
        <defs>
          <radialGradient id="sm2" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(253,177,73,0.35)" />
            <stop offset="100%" stopColor="rgba(253,177,73,0)" />
          </radialGradient>
        </defs>
        <ellipse cx="180" cy="80" rx="90" ry="70" fill="url(#sm2)" />
      </svg>
      <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
        <span style={{ fontSize: 28, fontWeight: 900, color: '#fdb149' }}>🧠</span>
        <span style={{ fontSize: 10, color: 'rgba(255,255,255,0.35)', letterSpacing: 3, textTransform: 'uppercase', marginTop: 4 }}>Data & AI</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=800 height=80
<div style={{ display: 'flex', gap: 8, padding: '14px 20px', width: '100%', height: '100%', background: '#06020a', borderRadius: 30, alignItems: 'center', justifyContent: 'center', fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden', border: '1px solid rgba(251,38,65,0.12)' }}>
  <style>{`
    @keyframes sk-a { 0%, 100% { transform: translate(0,0); opacity: 0.8; } 50% { transform: translate(24px,-8px); opacity: 1.1; } }
    @keyframes sk-b { 0%, 100% { transform: translate(0,0); opacity: 0.7; } 50% { transform: translate(-18px,10px); opacity: 1; } }
    #sko1 { animation: sk-a 7s ease-in-out infinite; }
    #sko2 { animation: sk-b 9s ease-in-out infinite; }
    #sko3 { animation: sk-a 6s ease-in-out infinite 0.4s; }
  `}</style>
  <svg width="800" height="80" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="skg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(251,38,65,0.55)" />
        <stop offset="100%" stopColor="rgba(251,38,65,0)" />
      </radialGradient>
      <radialGradient id="skg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(253,177,73,0.45)" />
        <stop offset="100%" stopColor="rgba(253,177,73,0)" />
      </radialGradient>
      <radialGradient id="skg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(254,149,105,0.4)" />
        <stop offset="100%" stopColor="rgba(254,149,105,0)" />
      </radialGradient>
    </defs>
    <ellipse id="sko1" cx="560" cy="90" rx="130" ry="60" fill="url(#skg1)" />
    <ellipse id="sko2" cx="680" cy="80" rx="120" ry="55" fill="url(#skg2)" />
    <ellipse id="sko3" cx="630" cy="100" rx="100" ry="50" fill="url(#skg3)" />
  </svg>
  {[
    { label: 'Python', color: '#fb2641' },
    { label: 'SQL', color: '#fb2641' },
    { label: 'Scikit-learn', color: '#fb2641' },
    { label: 'NetworkX', color: '#fb2641' },
    { label: 'TypeScript', color: '#fe9569' },
    { label: 'Next.js', color: '#fe9569' },
    { label: 'Java Spring', color: '#fe9569' },
    { label: 'Swift', color: '#fdb149' },
    { label: 'Groq', color: '#fdb149' },
    { label: 'Mistral', color: '#fdb149' },
  ].map((s, i) => (
    <span key={i} style={{ padding: '5px 14px', background: 'rgba(255,255,255,0.04)', color: s.color, borderRadius: 100, fontSize: 12, fontWeight: 600, border: `1px solid ${s.color}30`, fontFamily: 'monospace', letterSpacing: '0.02em' }}>{s.label}</span>
  ))}
</div>
```

```aura width=120 height=44 link="https://portfolio-terrel.vercel.app" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/vercel/ffffff"
  text="Portfolio"
  backgroundColor="#0a0005"
  width={120}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#fb2641' },
    { offset: '10%', color: '#200008' },
    { offset: '50%', color: '#fe9569' },
    { offset: '60%', color: '#fb2641' },
    { offset: '80%', color: '#200008' },
    { offset: '100%', color: '#fdb149' },
  ]}
/>
```

```aura width=130 height=44 link="https://linkedin.com/in/terrelnuentsa" inline align=center
<SocialMediaButton
  icon="https://raw.githubusercontent.com/simple-icons/simple-icons/develop/icons/linkedin.svg"
  text="LinkedIn"
  backgroundColor="#040e1a"
  width={130}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#fb2641' },
    { offset: '10%', color: '#040e1a' },
    { offset: '50%', color: '#fe9569' },
    { offset: '60%', color: '#fb2641' },
    { offset: '80%', color: '#040e1a' },
    { offset: '100%', color: '#fdb149' },
  ]}
/>
```

```aura width=120 height=44 link="https://github.com/binksterrell" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/github/ffffff"
  text="GitHub"
  backgroundColor="#080808"
  width={120}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#fb2641' },
    { offset: '10%', color: '#080808' },
    { offset: '50%', color: '#fe9569' },
    { offset: '60%', color: '#fb2641' },
    { offset: '80%', color: '#080808' },
    { offset: '100%', color: '#fdb149' },
  ]}
/>
```

```aura width=110 height=44 link="mailto:nuentsa.terrel@gmail.com" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/gmail/EA4335"
  text="Email"
  backgroundColor="#1a0404"
  width={110}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#fb2641' },
    { offset: '10%', color: '#1a0404' },
    { offset: '50%', color: '#fe9569' },
    { offset: '60%', color: '#fb2641' },
    { offset: '80%', color: '#1a0404' },
    { offset: '100%', color: '#fdb149' },
  ]}
/>
```
