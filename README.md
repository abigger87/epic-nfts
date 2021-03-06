# Epic NFTS

```
🚨​ Epic NFTs not deployed on Mainnet 🚨​
🚨​ Only deployed on Rinkeby Test network 🚨​
```

Main contract is: `contracts/EpicNFT.sol`

Contract ABI is generated at `artifacts/contracts/EpicNFT.sol/EpicNFT.json`

Account configuration for deployment is handled with environment variables.
Create a `.env` file in the base directory with the same variables as `.env.example`, but with values filled in.

### Compiling

```bash
npx hardhat compile
```

### Testing

```bash
npx hardhat test
```

### Mock Deploying

Run:

```bash
npx hardhat run scripts/run.js
```

### Deploying

Run:

```bash
npx hardhat run scripts/deploy.js --network rinkeby
```

## Epic Contract

A loot-inspired Dinosaurs and Caves game.

Version 4 (indexed events)
Contract: `0x9548a49f25b1C80FB451ec40cC0401C067D4F6AF`
[Opensea Collection](https://testnets.opensea.io/collection/the-epics-v2)

Version 3
Contract: `0x0a2315A245c0E9d3F0275e0733892Ed76Aa2d6d6`
[Opensea Collection](https://testnets.opensea.io/collection/the-epics)

Version 2
Contract: `0x908f9AfF6eE262946d5A350c2C0e0388670cf5E4`
[Opensea Collection](https://testnets.opensea.io/collection/epiccontract)


Version 1
Contract: `0x908f9AfF6eE262946d5A350c2C0e0388670cf5E4`
[Opensea Collection](https://testnets.opensea.io/collection/epiccontract)


## Useful Tools:

[JSON Keeper](https://jsonkeeper.com/)

[Base64 Encoder/Decoder](https://www.utilities-online.info/base64)

[Online SVG Viewer](https://www.svgviewer.dev/)

[Free Animated SVGs](https://getloaf.io/)


## Animated Contract NFT - not dynamic :/ yet...

Contract svg exists in `./assets/contract.svg`

### Base64 Encoded SVG

```
data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgdmlld0JveD0iMCAwIDEwMCAxMDAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgc3R5bGU9IndpZHRoOiAyMDBweDsgaGVpZ2h0OiAyMDBweDsiPjxzdHlsZT4KICAgICAubGluZS1maWxlMS1hIHthbmltYXRpb246bGluZS1maWxlMS1kcmF3IDNzIGluZmluaXRlOyBzdHJva2UtZGFzaGFycmF5OiAxMTA7fQogICAgIC5saW5lLWZpbGUxLWIge2FuaW1hdGlvbjpsaW5lLWZpbGUxLWRyYXcgM3MgMzAwbXMgaW5maW5pdGU7IHN0cm9rZS1kYXNoYXJyYXk6IDExMDsgc3Ryb2tlLWRhc2hvZmZzZXQ6IDEyMDt9CiAgICAgLmxpbmUtZmlsZTEtYyB7YW5pbWF0aW9uOmxpbmUtZmlsZTEtZHJhdyAzcyA2MDBtcyBpbmZpbml0ZTsgc3Ryb2tlLWRhc2hhcnJheTogMTEwOyBzdHJva2UtZGFzaG9mZnNldDogMTIwO30KICAgICBAa2V5ZnJhbWVzIGxpbmUtZmlsZTEtZHJhdyB7CiAgICAgICAgIDAle3N0cm9rZS1kYXNob2Zmc2V0OiAxMjA7fQogICAgICAgICAyMCV7c3Ryb2tlLWRhc2hvZmZzZXQ6IDEyMDt9CiAgICAgICAgIDgwJXtzdHJva2UtZGFzaG9mZnNldDogMDt9CiAgICAgICAgIDEwMCV7c3Ryb2tlLWRhc2hvZmZzZXQ6IC0xMTA7fQogICAgIH0KICAgICBAbWVkaWEgKHByZWZlcnMtcmVkdWNlZC1tb3Rpb246IHJlZHVjZSkgewogICAgICAgICAubGluZS1maWxlMS1hLCAubGluZS1maWxlMS1iLCAubGluZS1maWxlMS1jIHsKICAgICAgICAgICAgIGFuaW1hdGlvbjogbm9uZTsKICAgICAgICAgfQogICAgIH0KICAgIDwvc3R5bGU+PHBhdGggY2xhc3M9ImZpbGwxIiBkPSJNMTQgNlY5NEg4NlYzMC41SDYxLjVWNkgxNFoiIGZpbGw9InJnYmEoMjU1LDI0OSwyMzUsMSkiIHN0cm9rZS13aWR0aD0iMi4wcHgiPjwvcGF0aD48cGF0aCBjbGFzcz0iZmlsbDEiIGQ9Ik04NiAzMC41TDYxLjUgNlYzMC41SDg2WiIgZmlsbD0icmdiYSgyNTUsMjQ5LDIzNSwxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9wYXRoPjxwYXRoIGNsYXNzPSJzdHJva2UxIiBkPSJNODYgMzAuNVY5NEgxNFY2SDYxLjVNODYgMzAuNUw2MS41IDZNODYgMzAuNUg2MS41VjYiIHN0cm9rZT0icmdiYSgwLDAsMCwxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9wYXRoPjxsaW5lIGNsYXNzPSJsaW5lLWZpbGUxLWEgc3Ryb2tlMiIgeDE9IjI3LjUiIHkxPSIzMyIgeDI9IjQ4LjUiIHkyPSIzMyIgc3Ryb2tlPSJyZ2JhKDAsMTQzLDE3MywxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9saW5lPjxsaW5lIGNsYXNzPSJsaW5lLWZpbGUxLWIgc3Ryb2tlMiIgeDE9IjI3LjUiIHkxPSI1MyIgeDI9IjcxLjUiIHkyPSI1MyIgc3Ryb2tlPSJyZ2JhKDAsMTQzLDE3MywxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9saW5lPjxsaW5lIGNsYXNzPSJsaW5lLWZpbGUxLWMgc3Ryb2tlMiIgeDE9IjI3LjUiIHkxPSI3MyIgeDI9IjcxLjUiIHkyPSI3MyIgc3Ryb2tlPSJyZ2JhKDAsMTQzLDE3MywxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9saW5lPjwvc3ZnPg==
```


### Base64 Encoded Metadata

```
data:application/json;base64,ewogICAgIm5hbWUiOiAiRXBpY1NoYWRvd0NvbnRyYWN0IiwKICAgICJkZXNjcmlwdGlvbiI6ICJBIHJlcHJlc2VudGF0aW9uIG9mIHRoZSBlbmlnbWF0aWMgc2hhZG93eSBzbWFydCBjb250cmFjdC4iLAogICAgImltYWdlIjogImRhdGE6aW1hZ2Uvc3ZnK3htbDtiYXNlNjQsUEhOMlp5QjNhV1IwYUQwaU1UQXdJaUJvWldsbmFIUTlJakV3TUNJZ2RtbGxkMEp2ZUQwaU1DQXdJREV3TUNBeE1EQWlJR1pwYkd3OUltNXZibVVpSUhodGJHNXpQU0pvZEhSd09pOHZkM2QzTG5jekxtOXlaeTh5TURBd0wzTjJaeUlnYzNSNWJHVTlJbmRwWkhSb09pQXlNREJ3ZURzZ2FHVnBaMmgwT2lBeU1EQndlRHNpUGp4emRIbHNaVDRLSUNBZ0lDQXViR2x1WlMxbWFXeGxNUzFoSUh0aGJtbHRZWFJwYjI0NmJHbHVaUzFtYVd4bE1TMWtjbUYzSUROeklHbHVabWx1YVhSbE95QnpkSEp2YTJVdFpHRnphR0Z5Y21GNU9pQXhNVEE3ZlFvZ0lDQWdJQzVzYVc1bExXWnBiR1V4TFdJZ2UyRnVhVzFoZEdsdmJqcHNhVzVsTFdacGJHVXhMV1J5WVhjZ00zTWdNekF3YlhNZ2FXNW1hVzVwZEdVN0lITjBjbTlyWlMxa1lYTm9ZWEp5WVhrNklERXhNRHNnYzNSeWIydGxMV1JoYzJodlptWnpaWFE2SURFeU1EdDlDaUFnSUNBZ0xteHBibVV0Wm1sc1pURXRZeUI3WVc1cGJXRjBhVzl1T214cGJtVXRabWxzWlRFdFpISmhkeUF6Y3lBMk1EQnRjeUJwYm1acGJtbDBaVHNnYzNSeWIydGxMV1JoYzJoaGNuSmhlVG9nTVRFd095QnpkSEp2YTJVdFpHRnphRzltWm5ObGREb2dNVEl3TzMwS0lDQWdJQ0JBYTJWNVpuSmhiV1Z6SUd4cGJtVXRabWxzWlRFdFpISmhkeUI3Q2lBZ0lDQWdJQ0FnSURBbGUzTjBjbTlyWlMxa1lYTm9iMlptYzJWME9pQXhNakE3ZlFvZ0lDQWdJQ0FnSUNBeU1DVjdjM1J5YjJ0bExXUmhjMmh2Wm1aelpYUTZJREV5TUR0OUNpQWdJQ0FnSUNBZ0lEZ3dKWHR6ZEhKdmEyVXRaR0Z6YUc5bVpuTmxkRG9nTUR0OUNpQWdJQ0FnSUNBZ0lERXdNQ1Y3YzNSeWIydGxMV1JoYzJodlptWnpaWFE2SUMweE1UQTdmUW9nSUNBZ0lIMEtJQ0FnSUNCQWJXVmthV0VnS0hCeVpXWmxjbk10Y21Wa2RXTmxaQzF0YjNScGIyNDZJSEpsWkhWalpTa2dld29nSUNBZ0lDQWdJQ0F1YkdsdVpTMW1hV3hsTVMxaExDQXViR2x1WlMxbWFXeGxNUzFpTENBdWJHbHVaUzFtYVd4bE1TMWpJSHNLSUNBZ0lDQWdJQ0FnSUNBZ0lHRnVhVzFoZEdsdmJqb2dibTl1WlRzS0lDQWdJQ0FnSUNBZ2ZRb2dJQ0FnSUgwS0lDQWdJRHd2YzNSNWJHVStQSEJoZEdnZ1kyeGhjM005SW1acGJHd3hJaUJrUFNKTk1UUWdObFk1TkVnNE5sWXpNQzQxU0RZeExqVldOa2d4TkZvaUlHWnBiR3c5SW5KblltRW9NalUxTERJME9Td3lNelVzTVNraUlITjBjbTlyWlMxM2FXUjBhRDBpTWk0d2NIZ2lQand2Y0dGMGFENDhjR0YwYUNCamJHRnpjejBpWm1sc2JERWlJR1E5SWswNE5pQXpNQzQxVERZeExqVWdObFl6TUM0MVNEZzJXaUlnWm1sc2JEMGljbWRpWVNneU5UVXNNalE1TERJek5Td3hLU0lnYzNSeWIydGxMWGRwWkhSb1BTSXlMakJ3ZUNJK1BDOXdZWFJvUGp4d1lYUm9JR05zWVhOelBTSnpkSEp2YTJVeElpQmtQU0pOT0RZZ016QXVOVlk1TkVneE5GWTJTRFl4TGpWTk9EWWdNekF1TlV3Mk1TNDFJRFpOT0RZZ016QXVOVWcyTVM0MVZqWWlJSE4wY205clpUMGljbWRpWVNnd0xEQXNNQ3d4S1NJZ2MzUnliMnRsTFhkcFpIUm9QU0l5TGpCd2VDSStQQzl3WVhSb1BqeHNhVzVsSUdOc1lYTnpQU0pzYVc1bExXWnBiR1V4TFdFZ2MzUnliMnRsTWlJZ2VERTlJakkzTGpVaUlIa3hQU0l6TXlJZ2VESTlJalE0TGpVaUlIa3lQU0l6TXlJZ2MzUnliMnRsUFNKeVoySmhLREFzTVRRekxERTNNeXd4S1NJZ2MzUnliMnRsTFhkcFpIUm9QU0l5TGpCd2VDSStQQzlzYVc1bFBqeHNhVzVsSUdOc1lYTnpQU0pzYVc1bExXWnBiR1V4TFdJZ2MzUnliMnRsTWlJZ2VERTlJakkzTGpVaUlIa3hQU0kxTXlJZ2VESTlJamN4TGpVaUlIa3lQU0kxTXlJZ2MzUnliMnRsUFNKeVoySmhLREFzTVRRekxERTNNeXd4S1NJZ2MzUnliMnRsTFhkcFpIUm9QU0l5TGpCd2VDSStQQzlzYVc1bFBqeHNhVzVsSUdOc1lYTnpQU0pzYVc1bExXWnBiR1V4TFdNZ2MzUnliMnRsTWlJZ2VERTlJakkzTGpVaUlIa3hQU0kzTXlJZ2VESTlJamN4TGpVaUlIa3lQU0kzTXlJZ2MzUnliMnRsUFNKeVoySmhLREFzTVRRekxERTNNeXd4S1NJZ2MzUnliMnRsTFhkcFpIUm9QU0l5TGpCd2VDSStQQzlzYVc1bFBqd3ZjM1puUGc9PSIKfQ==
```

Metadata:

```
{
    "name": "EpicShadowContract",
    "description": "A representation of the enigmatic shadowy smart contract.",
    "image": "data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgdmlld0JveD0iMCAwIDEwMCAxMDAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgc3R5bGU9IndpZHRoOiAyMDBweDsgaGVpZ2h0OiAyMDBweDsiPjxzdHlsZT4KICAgICAubGluZS1maWxlMS1hIHthbmltYXRpb246bGluZS1maWxlMS1kcmF3IDNzIGluZmluaXRlOyBzdHJva2UtZGFzaGFycmF5OiAxMTA7fQogICAgIC5saW5lLWZpbGUxLWIge2FuaW1hdGlvbjpsaW5lLWZpbGUxLWRyYXcgM3MgMzAwbXMgaW5maW5pdGU7IHN0cm9rZS1kYXNoYXJyYXk6IDExMDsgc3Ryb2tlLWRhc2hvZmZzZXQ6IDEyMDt9CiAgICAgLmxpbmUtZmlsZTEtYyB7YW5pbWF0aW9uOmxpbmUtZmlsZTEtZHJhdyAzcyA2MDBtcyBpbmZpbml0ZTsgc3Ryb2tlLWRhc2hhcnJheTogMTEwOyBzdHJva2UtZGFzaG9mZnNldDogMTIwO30KICAgICBAa2V5ZnJhbWVzIGxpbmUtZmlsZTEtZHJhdyB7CiAgICAgICAgIDAle3N0cm9rZS1kYXNob2Zmc2V0OiAxMjA7fQogICAgICAgICAyMCV7c3Ryb2tlLWRhc2hvZmZzZXQ6IDEyMDt9CiAgICAgICAgIDgwJXtzdHJva2UtZGFzaG9mZnNldDogMDt9CiAgICAgICAgIDEwMCV7c3Ryb2tlLWRhc2hvZmZzZXQ6IC0xMTA7fQogICAgIH0KICAgICBAbWVkaWEgKHByZWZlcnMtcmVkdWNlZC1tb3Rpb246IHJlZHVjZSkgewogICAgICAgICAubGluZS1maWxlMS1hLCAubGluZS1maWxlMS1iLCAubGluZS1maWxlMS1jIHsKICAgICAgICAgICAgIGFuaW1hdGlvbjogbm9uZTsKICAgICAgICAgfQogICAgIH0KICAgIDwvc3R5bGU+PHBhdGggY2xhc3M9ImZpbGwxIiBkPSJNMTQgNlY5NEg4NlYzMC41SDYxLjVWNkgxNFoiIGZpbGw9InJnYmEoMjU1LDI0OSwyMzUsMSkiIHN0cm9rZS13aWR0aD0iMi4wcHgiPjwvcGF0aD48cGF0aCBjbGFzcz0iZmlsbDEiIGQ9Ik04NiAzMC41TDYxLjUgNlYzMC41SDg2WiIgZmlsbD0icmdiYSgyNTUsMjQ5LDIzNSwxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9wYXRoPjxwYXRoIGNsYXNzPSJzdHJva2UxIiBkPSJNODYgMzAuNVY5NEgxNFY2SDYxLjVNODYgMzAuNUw2MS41IDZNODYgMzAuNUg2MS41VjYiIHN0cm9rZT0icmdiYSgwLDAsMCwxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9wYXRoPjxsaW5lIGNsYXNzPSJsaW5lLWZpbGUxLWEgc3Ryb2tlMiIgeDE9IjI3LjUiIHkxPSIzMyIgeDI9IjQ4LjUiIHkyPSIzMyIgc3Ryb2tlPSJyZ2JhKDAsMTQzLDE3MywxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9saW5lPjxsaW5lIGNsYXNzPSJsaW5lLWZpbGUxLWIgc3Ryb2tlMiIgeDE9IjI3LjUiIHkxPSI1MyIgeDI9IjcxLjUiIHkyPSI1MyIgc3Ryb2tlPSJyZ2JhKDAsMTQzLDE3MywxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9saW5lPjxsaW5lIGNsYXNzPSJsaW5lLWZpbGUxLWMgc3Ryb2tlMiIgeDE9IjI3LjUiIHkxPSI3MyIgeDI9IjcxLjUiIHkyPSI3MyIgc3Ryb2tlPSJyZ2JhKDAsMTQzLDE3MywxKSIgc3Ryb2tlLXdpZHRoPSIyLjBweCI+PC9saW5lPjwvc3ZnPg=="
}
```