## HLAB networks:

- **192.168.0.0/24**    main local, physics+wifi, router - owrt (dlink 645), sub-routers: ywrt (orange r1), powrt (pve3), dlink (1210)

  1. rshdmz (wire)
  2. smart plugs (wifi wep2+mac filter)
  3. pve3 (wire)
- **192.168.200.0/24**  local guest, physics+wifi, router - owrt (dlink 645), sub-routers: ywrt (orange r1), powrt (pve3), dlink (1210)

  1. ywrt (wire)
  2. qnap s2
  3. any wifi clients (wep3)
- **192.168.201.0/24**  local guest, physics, router - ywrt (orange r1)

  1. tvbox w2
- **192.168.100.0/24** local pve, physics, router - powrt (pve vm)

  1. pve[x]
  2. dlink 1210
- **11.0.0.0/24**       virtual pve, router - powrt (pve vm)
- **10.0.0.0/24**        wireguard, router - ywrt (orange r1)
