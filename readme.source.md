```aura width=800 height=210
<div style={{
  display: 'flex',
  flexDirection: 'column',
  alignItems: 'center',
  justifyContent: 'center',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #141414 0%, #0d0d0d 60%, #050505 100%)',
  borderRadius: '16px',
  border: '1px solid #2a2a2a',
  gap: '18px',
  position: 'relative',
  overflow: 'hidden',
}}>
  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '0',
    left: '0',
    right: '0',
    height: '3px',
    background: 'linear-gradient(90deg, #ffffff 0%, #8a8a8a 50%, #3a3a3a 100%)',
  }} />

  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '-60px',
    right: '-60px',
    width: '200px',
    height: '200px',
    borderRadius: '50%',
    background: 'radial-gradient(circle, rgba(255,255,255,0.06) 0%, transparent 70%)',
  }} />

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: '20px',
  }}>
    <div style={{
      display: 'flex',
      width: '76px',
      height: '76px',
      borderRadius: '50%',
      background: 'linear-gradient(135deg, #ffffff, #9a9a9a, #3a3a3a)',
      alignItems: 'center',
      justifyContent: 'center',
    }}>
      <div style={{
        display: 'flex',
        width: '70px',
        height: '70px',
        borderRadius: '50%',
        overflow: 'hidden',
        border: '2px solid #0d0d0d',
      }}>
        <img
          src="https://github.com/kayasolomon.png"
          style={{
            width: '70px',
            height: '70px',
          }}
        />
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', gap: '5px' }}>
      <span style={{
        fontSize: '38px',
        fontWeight: '700',
        color: '#f5f5f5',
        letterSpacing: '-1px',
      }}>
        kayasolomon
      </span>
      <span style={{
        fontSize: '14px',
        color: '#9a9a9a',
        fontWeight: '500',
        letterSpacing: '1.5px',
        textTransform: 'uppercase',
      }}>
        finance · quant · machine learning
      </span>
    </div>
  </div>

  <div style={{ display: 'flex', gap: '8px' }}>
    {[
      { tag: 'python',     bg: 'rgba(255,255,255,0.10)', border: '#f5f5f5', color: '#f5f5f5' },
      { tag: 'typescript', bg: 'rgba(255,255,255,0.08)', border: '#c0c0c0', color: '#c0c0c0' },
      { tag: 'ml',         bg: 'rgba(255,255,255,0.06)', border: '#9a9a9a', color: '#9a9a9a' },
      { tag: 'markets',    bg: 'rgba(255,255,255,0.04)', border: '#7a7a7a', color: '#7a7a7a' },
    ].map(({ tag, bg, border, color }) => (
      <div key={tag} style={{
        display: 'flex',
        padding: '4px 14px',
        borderRadius: '999px',
        background: bg,
        border: `1px solid ${border}`,
        color: color,
        fontSize: '12px',
        fontWeight: '700',
        letterSpacing: '0.8px',
        textTransform: 'uppercase',
      }}>
        {tag}
      </div>
    ))}
  </div>
</div>
```

```aura width=800 height=130
<div style={{
  display: 'flex',
  alignItems: 'stretch',
  width: '100%',
  height: '100%',
  background: '#0d0d0d',
  borderRadius: '16px',
  border: '1px solid #2a2a2a',
  overflow: 'hidden',
}}>
  {[
    { label: 'Email',   value: 'kaya.solomon24@gmail.com', color: '#f5f5f5', accent: '#f5f5f5' },
    { label: 'Website', value: 'kayasolomon.tech',         color: '#c0c0c0', accent: '#c0c0c0' },
    { label: 'GitHub',  value: '@kayasolomon',             color: '#9a9a9a', accent: '#9a9a9a' },
  ].map((item, i) => (
    <div key={i} style={{
      display: 'flex',
      flex: '1',
      flexDirection: 'column',
      alignItems: 'center',
      justifyContent: 'center',
      gap: '7px',
      borderRight: i < 2 ? '1px solid #2a2a2a' : 'none',
      position: 'relative',
      overflow: 'hidden',
    }}>
      <div style={{
        display: 'flex',
        position: 'absolute',
        bottom: '0',
        left: '20%',
        right: '20%',
        height: '2px',
        background: item.accent,
        borderRadius: '2px',
        opacity: '0.6',
      }} />

      <span style={{
        fontSize: '11px',
        color: '#6a6a6a',
        fontWeight: '700',
        letterSpacing: '1.2px',
        textTransform: 'uppercase',
      }}>
        {item.label}
      </span>

      <span style={{
        fontSize: '13px',
        color: item.color,
        fontWeight: '600',
        letterSpacing: '0.2px',
      }}>
        {item.value}
      </span>
    </div>
  ))}
</div>
```

[![GitHub Stats](https://ghstats.dev/api/card?username=kayasolomon&theme=dark&bg=0a0a0a&text=e8e8e8&title_color=ffffff&icon_color=8a8a8a&border_color=2a2a2a&hide=trend%2Cavg%2Cactive_day%2Cgrade%2Ccontributions%2Crepos%2Cfollowers&custom_title=Stats&border_radius=10)](https://github.com/kayasolomon)
