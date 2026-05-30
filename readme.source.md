```aura width=800 height=280
<div style={{ display: 'flex', width: '100%', height: '100%', background: '#E8221A', borderRadius: 20, overflow: 'hidden', position: 'relative', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes star-spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    @keyframes star-float { 0%, 100% { transform: translateY(0px) rotate(0deg); opacity: 0.12; } 50% { transform: translateY(-12px) rotate(180deg); opacity: 0.22; } }
    @keyframes star-float-b { 0%, 100% { transform: translateY(0px) rotate(45deg); opacity: 0.08; } 50% { transform: translateY(10px) rotate(225deg); opacity: 0.18; } }
    @keyframes pill-pulse { 0%, 100% { opacity: 0.85; } 50% { opacity: 1; } }
    #hs1 { animation: star-float 7s ease-in-out infinite; }
    #hs2 { animation: star-float-b 9s ease-in-out infinite 1s; }
    #hs3 { animation: star-float 6s ease-in-out infinite 2s; }
    #hs4 { animation: star-float-b 8s ease-in-out infinite 0.5s; }
    #hs5 { animation: star-float 10s ease-in-out infinite 3s; }
    #hs6 { animation: star-float-b 7s ease-in-out infinite 1.5s; }
    #hpill { animation: pill-pulse 3s ease-in-out infinite; }
  `}</style>

  <svg width="800" height="280" style={{ position: 'absolute', top: 0, left: 0 }}>
    <polygon id="hs1" points="60,20 65,36 82,36 69,46 74,62 60,52 46,62 51,46 38,36 55,36" fill="#000" opacity="0.12" />
    <polygon id="hs2" points="740,30 744,42 757,42 747,50 751,62 740,54 729,62 733,50 723,42 736,42" fill="#000" opacity="0.08" />
    <polygon id="hs3" points="120,220 124,232 137,232 127,240 131,252 120,244 109,252 113,240 103,232 116,232" fill="#fff" opacity="0.1" />
    <polygon id="hs4" points="700,200 706,218 725,218 710,230 716,248 700,236 684,248 690,230 675,218 694,218" fill="#000" opacity="0.1" />
    <polygon id="hs5" points="400,240 403,250 414,250 405,257 408,267 400,261 392,267 395,257 386,250 397,250" fill="#fff" opacity="0.08" />
    <polygon id="hs6" points="50,120 54,132 67,132 57,140 61,152 50,144 39,152 43,140 33,132 46,132" fill="#fff" opacity="0.07" />
    <line x1="0" y1="70" x2="800" y2="70" stroke="rgba(0,0,0,0.06)" strokeWidth="1" />
    <line x1="0" y1="140" x2="800" y2="140" stroke="rgba(0,0,0,0.06)" strokeWidth="1" />
    <line x1="0" y1="210" x2="800" y2="210" stroke="rgba(0,0,0,0.06)" strokeWidth="1" />
    <line x1="160" y1="0" x2="160" y2="280" stroke="rgba(0,0,0,0.04)" strokeWidth="1" />
    <line x1="320" y1="0" x2="320" y2="280" stroke="rgba(0,0,0,0.04)" strokeWidth="1" />
    <line x1="480" y1="0" x2="480" y2="280" stroke="rgba(0,0,0,0.04)" strokeWidth="1" />
    <line x1="640" y1="0" x2="640" y2="280" stroke="rgba(0,0,0,0.04)" strokeWidth="1" />
  </svg>

  <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '0 52px', flex: 1 }}>
    <div id="hpill" style={{ display: 'flex', alignItems: 'center', gap: 7, padding: '5px 14px', borderRadius: 9999, background: 'rgba(0,0,0,0.15)', border: '1px solid rgba(0,0,0,0.2)', marginBottom: 24, alignSelf: 'flex-start' }}>
      <span style={{ width: 6, height: 6, borderRadius: '50%', background: '#000', display: 'flex' }} />
      <span style={{ fontSize: 10, color: '#000', fontWeight: 700, letterSpacing: '0.08em', textTransform: 'uppercase' }}>Ouvert aux alternances · Data / AI · Sept. 2026</span>
    </div>
    <div style={{ display: 'flex', alignItems: 'baseline', gap: 0 }}>
      <span style={{ fontSize: 68, fontWeight: 900, color: '#000', letterSpacing: '-3px', lineHeight: 1 }}>Terrel</span>
      <span style={{ fontSize: 68, fontWeight: 900, color: '#fff', letterSpacing: '-3px', lineHeight: 1 }}>&nbsp;NUENTSA</span>
    </div>
    <span style={{ fontSize: 13, color: 'rgba(0,0,0,0.5)', marginTop: 14, letterSpacing: '0.14em', textTransform: 'uppercase', fontWeight: 600 }}>Concevoir · Coder · Déployer</span>
  </div>

  <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'center', padding: '0 40px 0 0', flexShrink: 0 }}>
    <img src="data:image/png;base64,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" width={160} height={160} style={{ borderRadius: 28 }} />
  </div>
</div>
```

```aura width=800 height=240
<div style={{ display: 'flex', flexDirection: 'row', gap: 14, width: '100%', height: '100%', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes ab-a { 0%, 100% { transform: translate(0,0); opacity: 0.6; } 50% { transform: translate(18px,-14px); opacity: 0.9; } }
    @keyframes ab-b { 0%, 100% { transform: translate(0,0); opacity: 0.5; } 50% { transform: translate(-14px,10px); opacity: 0.75; } }
    @keyframes ab-cur { 0%, 49% { opacity: 1; } 50%, 99% { opacity: 0; } }
    @keyframes ab-scan { 0% { transform: translateY(-30px); opacity: 0.3; } 100% { transform: translateY(240px); opacity: 0; } }
    @keyframes ab-dot { 0%, 100% { opacity: 0.3; } 50% { opacity: 1; } }
    #abo1 { animation: ab-a 8s ease-in-out infinite; }
    #abo2 { animation: ab-b 10s ease-in-out infinite 1s; }
    #abo3 { animation: ab-a 7s ease-in-out infinite 2s; }
    #ab-cursor { animation: ab-cur 1.1s step-end infinite; }
    #ab-scan { animation: ab-scan 3s linear infinite; }
    #abd1 { animation: ab-dot 2s ease-in-out infinite; }
    #abd2 { animation: ab-dot 2s ease-in-out infinite 0.66s; }
    #abd3 { animation: ab-dot 2s ease-in-out infinite 1.33s; }
  `}</style>
  <div style={{ position: 'relative', display: 'flex', flex: 1, height: '100%', background: '#0a0000', borderRadius: 16, overflow: 'hidden', border: '1px solid rgba(232,34,26,0.3)' }}>
    <svg width="100%" height="240" style={{ position: 'absolute', top: 0, left: 0 }}>
      <defs>
        <radialGradient id="abg1" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="rgba(232,34,26,0.6)" />
          <stop offset="100%" stopColor="rgba(232,34,26,0)" />
        </radialGradient>
        <radialGradient id="abg2" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stopColor="rgba(232,34,26,0.3)" />
          <stop offset="100%" stopColor="rgba(232,34,26,0)" />
        </radialGradient>
        <linearGradient id="ab-scan-grad" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stopColor="rgba(232,34,26,0)" />
          <stop offset="50%" stopColor="rgba(232,34,26,0.12)" />
          <stop offset="100%" stopColor="rgba(232,34,26,0)" />
        </linearGradient>
      </defs>
      <ellipse id="abo1" cx="40"  cy="200" rx="130" ry="110" fill="url(#abg1)" />
      <ellipse id="abo2" cx="380" cy="30"  rx="110" ry="95"  fill="url(#abg2)" />
      <ellipse id="abo3" cx="300" cy="220" rx="95"  ry="85"  fill="url(#abg2)" />
      <rect id="ab-scan" x="0" y="-30" width="100%" height="30" fill="url(#ab-scan-grad)" />
    </svg>
    <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '0 32px' }}>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 14 }}>
        <span style={{ fontSize: 9, color: '#E8221A', letterSpacing: 5, textTransform: 'uppercase', fontWeight: 700 }}>À propos</span>
        <div style={{ display: 'flex', gap: 4, marginLeft: 8 }}>
          <span id="abd1" style={{ width: 4, height: 4, borderRadius: '50%', background: '#E8221A', display: 'flex' }} />
          <span id="abd2" style={{ width: 4, height: 4, borderRadius: '50%', background: '#E8221A', display: 'flex', opacity: '0.6' }} />
          <span id="abd3" style={{ width: 4, height: 4, borderRadius: '50%', background: '#E8221A', display: 'flex', opacity: '0.3' }} />
        </div>
      </div>
      <span style={{ fontSize: 22, fontWeight: 900, color: '#ffffff', lineHeight: 1.2, letterSpacing: '-0.5px' }}>Étudiant ingénieur</span>
      <span style={{ fontSize: 22, fontWeight: 900, lineHeight: 1.2, letterSpacing: '-0.5px', color: '#E8221A' }}>en Data & IA.</span>
      <span style={{ fontSize: 12, color: 'rgba(255,255,255,0.45)', marginTop: 12, lineHeight: 1.6, maxWidth: 300 }}>Profil hybride Maths & Informatique. Je construis des pipelines de données, des modèles ML et des apps full-stack — de l'idée au déploiement.</span>
      <div style={{ display: 'flex', alignItems: 'center', marginTop: 14, background: 'rgba(232,34,26,0.08)', border: '1px solid rgba(232,34,26,0.2)', borderRadius: 8, padding: '6px 12px', alignSelf: 'flex-start' }}>
        <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.4)', fontFamily: 'monospace' }}>{'> EDF · M1 MIAGE Dauphine · Sept. 2026'}</span>
        <span id="ab-cursor" style={{ fontSize: 11, color: '#E8221A', fontFamily: 'monospace', marginLeft: 1 }}>_</span>
      </div>
    </div>
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: 14, width: 200, flexShrink: 0 }}>
    <div style={{ display: 'flex', flex: 1, background: '#E8221A', borderRadius: 14, overflow: 'hidden', alignItems: 'center', justifyContent: 'center' }}>
      <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
        <span style={{ fontSize: 32 }}>🏀</span>
        <span style={{ fontSize: 9, color: 'rgba(0,0,0,0.7)', letterSpacing: 4, textTransform: 'uppercase', marginTop: 6, fontWeight: 700 }}>NBA fan</span>
        <span style={{ fontSize: 9, color: 'rgba(0,0,0,0.5)', letterSpacing: 2, textTransform: 'uppercase', marginTop: 2 }}>Swish Tac Toe</span>
      </div>
    </div>
    <div style={{ display: 'flex', flex: 1, background: '#E8221A', borderRadius: 14, overflow: 'hidden', alignItems: 'center', justifyContent: 'center' }}>
      <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
        <span style={{ fontSize: 32 }}>⚡</span>
        <span style={{ fontSize: 9, color: 'rgba(0,0,0,0.7)', letterSpacing: 4, textTransform: 'uppercase', marginTop: 6, fontWeight: 700 }}>Alternance</span>
        <span style={{ fontSize: 9, color: 'rgba(0,0,0,0.5)', letterSpacing: 2, textTransform: 'uppercase', marginTop: 2 }}>Data / AI</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=800 height=200
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0000', borderRadius: 16, overflow: 'hidden', fontFamily: 'monospace', border: '1px solid rgba(232,34,26,0.25)', position: 'relative' }}>
  <style>{`
    @keyframes tm-cur { 0%, 49% { opacity: 1; } 50%, 99% { opacity: 0; } }
    @keyframes tm-l1 { 0%,9%{opacity:0} 10%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l2 { 0%,19%{opacity:0} 20%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l3 { 0%,29%{opacity:0} 30%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l4 { 0%,39%{opacity:0} 40%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l5 { 0%,49%{opacity:0} 50%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l6 { 0%,59%{opacity:0} 60%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l7 { 0%,69%{opacity:0} 70%,92%{opacity:1} 93%,100%{opacity:0} }
    @keyframes tm-l8 { 0%,79%{opacity:0} 80%,92%{opacity:1} 93%,100%{opacity:0} }
    #tm-cur { animation: tm-cur 1s step-end infinite; }
    #tl1 { animation: tm-l1 8s ease-in-out infinite; }
    #tl2 { animation: tm-l2 8s ease-in-out infinite; }
    #tl3 { animation: tm-l3 8s ease-in-out infinite; }
    #tl4 { animation: tm-l4 8s ease-in-out infinite; }
    #tl5 { animation: tm-l5 8s ease-in-out infinite; }
    #tl6 { animation: tm-l6 8s ease-in-out infinite; }
    #tl7 { animation: tm-l7 8s ease-in-out infinite; }
    #tl8 { animation: tm-l8 8s ease-in-out infinite; }
  `}</style>
  <svg width="800" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="tmg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(232,34,26,0.4)" />
        <stop offset="100%" stopColor="rgba(232,34,26,0)" />
      </radialGradient>
    </defs>
    <ellipse cx="700" cy="160" rx="200" ry="160" fill="url(#tmg1)" />
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', padding: '20px 28px', gap: 0 }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 16 }}>
      <div style={{ width: 10, height: 10, borderRadius: '50%', background: '#E8221A' }} />
      <div style={{ width: 10, height: 10, borderRadius: '50%', background: 'rgba(232,34,26,0.5)' }} />
      <div style={{ width: 10, height: 10, borderRadius: '50%', background: 'rgba(232,34,26,0.2)' }} />
      <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.2)', marginLeft: 10, letterSpacing: 2 }}>terrel@macbook ~ %</span>
    </div>
    <div id="tl1" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: '#E8221A', fontSize: 13 }}>$</span>
      <span style={{ color: 'rgba(255,255,255,0.7)', fontSize: 13 }}>{'git commit -m "feat: pipeline SharePoint LLM @ EDF"'}</span>
    </div>
    <div id="tl2" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: 'rgba(255,255,255,0.2)', fontSize: 13 }}>{'→'}</span>
      <span style={{ color: 'rgba(255,255,255,0.3)', fontSize: 13 }}>{'2 200+ entrees traitees · branch main'}</span>
    </div>
    <div id="tl3" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: '#E8221A', fontSize: 13 }}>$</span>
      <span style={{ color: 'rgba(255,255,255,0.7)', fontSize: 13 }}>{'python train.py --model random_forest --dataset banquise'}</span>
    </div>
    <div id="tl4" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: 'rgba(255,255,255,0.2)', fontSize: 13 }}>{'→'}</span>
      <span style={{ color: 'rgba(255,255,255,0.3)', fontSize: 13 }}>{'accuracy: 0.94 · f1: 0.91 · saved to /models'}</span>
    </div>
    <div id="tl5" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: '#E8221A', fontSize: 13 }}>$</span>
      <span style={{ color: 'rgba(255,255,255,0.7)', fontSize: 13 }}>{'npx vercel deploy --prod'}</span>
    </div>
    <div id="tl6" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: 'rgba(255,255,255,0.2)', fontSize: 13 }}>{'→'}</span>
      <span style={{ color: 'rgba(255,255,255,0.3)', fontSize: 13 }}>{'portfolio-terrel.vercel.app · 1.2s'}</span>
    </div>
    <div id="tl7" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: '#E8221A', fontSize: 13 }}>$</span>
      <span style={{ color: 'rgba(255,255,255,0.7)', fontSize: 13 }}>{'nx build episteme --graph --algo louvain'}</span>
    </div>
    <div id="tl8" style={{ display: 'flex', gap: 8, marginBottom: 5 }}>
      <span style={{ color: 'rgba(255,255,255,0.2)', fontSize: 13 }}>{'→'}</span>
      <span style={{ color: 'rgba(255,255,255,0.3)', fontSize: 13 }}>{'1 703 nodes · 12 communities · pagerank done'}</span>
    </div>
    <div style={{ display: 'flex', gap: 8, marginTop: 2 }}>
      <span style={{ color: '#E8221A', fontSize: 13 }}>$</span>
      <span id="tm-cur" style={{ color: '#E8221A', fontSize: 13 }}>{'▋'}</span>
    </div>
  </div>
</div>
```
```aura width=120 height=44 link="https://portfolio-terrel.vercel.app" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/vercel/ffffff"
  text="Portfolio"
  backgroundColor="#E8221A"
  width={120}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '20%', color: '#E8221A' },
    { offset: '50%', color: '#ff6b6b' },
    { offset: '80%', color: '#E8221A' },
    { offset: '100%', color: '#ffffff' },
  ]}
/>
```

```aura width=130 height=44 link="https://linkedin.com/in/terrelnuentsa" inline align=center
<SocialMediaButton
  icon="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/240px-LinkedIn_logo_initials.png"
  text="LinkedIn"
  backgroundColor="#000000"
  width={130}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '20%', color: '#E8221A' },
    { offset: '50%', color: '#ff6b6b' },
    { offset: '80%', color: '#E8221A' },
    { offset: '100%', color: '#ffffff' },
  ]}
/>
```

```aura width=120 height=44 link="https://github.com/binksterrel" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/github/ffffff"
  text="GitHub"
  backgroundColor="#000000"
  width={120}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '20%', color: '#E8221A' },
    { offset: '50%', color: '#ff6b6b' },
    { offset: '80%', color: '#E8221A' },
    { offset: '100%', color: '#ffffff' },
  ]}
/>
```

```aura width=110 height=44 link="mailto:nuentsa.terrel@gmail.com" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/gmail/ffffff"
  text="Email"
  backgroundColor="#000000"
  width={110}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '20%', color: '#E8221A' },
    { offset: '50%', color: '#ff6b6b' },
    { offset: '80%', color: '#E8221A' },
    { offset: '100%', color: '#ffffff' },
  ]}
/>
```
