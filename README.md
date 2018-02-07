# Entanglement
/ɪnˈtaŋɡ(ə)lm(ə)nt,ɛnˈtaŋɡ(ə)lm(ə)nt/

When we look at particles, we usually say that each particle has its own quantum state. Sometimes, two particles can act on one another and become an entangled system. When a pair or group of particles can only be described by the quantum state for the system, and not by individual quantum states, we say the particles are "entangled".

## Entangled RTCPeerconnections

When to peerconnections are entangled, actions happening on one of them are reflected on the other.
```

      Browser                                 Browser
     +-------------+                  +--------------+
     |             |                  |              |
     |             |                  |              |
     |      +----+ |     datachannel  | +----+       |
     |      | PC <----------------------> PC |       |
     |      +--^-+ |                  | +----+       |
     +--------+ +--+                  +--+ +---------+
               +                          +
               +                          v
             addTrack()                 onaddtrack()

````
