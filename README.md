# juniper_mpls_l2_vpn_config
DC-DC l2 interconnect. it is working few years


Debugging:

root> show l2circuit connections 
Layer-2 Circuit Connections:

Legend for connection status (St)   
EI -- encapsulation invalid      NP -- interface h/w not present   
MM -- mtu mismatch               Dn -- down                       
EM -- encapsulation mismatch     VC-Dn -- Virtual circuit Down    
CM -- control-word mismatch      Up -- operational                
VM -- vlan id mismatch           CF -- Call admission control failure
OL -- no outgoing label          IB -- TDM incompatible bitrate 
NC -- intf encaps not CCC/TCC    TM -- TDM misconfiguration 
BK -- Backup Connection          ST -- Standby Connection
CB -- rcvd cell-bundle size bad  SP -- Static Pseudowire
LD -- local site signaled down   RS -- remote site standby
RD -- remote site signaled down  XX -- unknown

Legend for interface status  
Up -- operational            
Dn -- down                   
Neighbor: 10.255.255.1 
    Interface                 Type  St     Time last up          # Up trans
    ge-0/0/1.0(vc 509)        rmt   Up     Oct 10 06:44:34 2019           1
      Remote PE: 10.255.255.1, Negotiated control-word: No
      Incoming label: 299776, Outgoing label: 299776
      Negotiated PW status TLV: No
      Local interface: ge-0/0/1.0, Status: Up, Encapsulation: ETHERNET
