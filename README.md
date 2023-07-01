# Deterministic RSA Key Pair generator

## Installation

```
pip install drkp
```

## Usage

```python
>>> import drkp
>>> key = drkp.Key(seed='xyzzy')
>>> key.private
b'-----BEGIN RSA PRIVATE KEY-----\nMIIEqwIBAAKCAQEAsnR7u0gCuJlcuHZxR8iDrFhPEb22jkSYlXQtv8V2PD6+7jwo\nCpsx0krcy5qmIFgqHoRTs3BCGxB3Q/pobp8KZQ4LwXDrqS630EAMTs25DOOaADga\nLceBWzTL66AwsHdNVKeGmtCNTYpnxSp3upL/uYxEzmlfmaQKLJY5Px2Z2/gNfd45\nRThIIPRAQBDyIYdzBGj7X+s1AQlBd8cUID+nEUmPPEzxr0Hdlffs5N4alqTtfsCk\n0Qp5ymOfqpgua3OOfQjcADXXB1GzWN5YMQtuIbITiCxGKvMdoQzPGrLvGpOapA7K\nKwPXKdJbW7kyhSD9zgn+en3RCl1LfCT5aihAtwIDAQABAoIBAQCrJNNVNSaG623k\n6pKRiVfefYK3PP5LSrYa/ySw+ir+dB6gU8kDAvuw9mLyUQppkqQySC4NtOdxFUWM\nSCbHkHdjmyjjB+y6gDeA3Svwl5OVLOKQuz1AEkmYsvWusB6B3qinO1L4PnKFnusO\nSEAzCq99v2xtmNk6e/soTmVKmIFOAAXebqYGpchf3e7xzRKAa7Bxfhd0u59JyO24\nvO+0N77VtTjO3dEBF3mI5aSPi+5R23u8C27aCiEIHIXUE9DT3v5HFeewv3tiCOzP\nAQXDxFlPJe77AAq0x4PEe97KKcAt+HGDmQcEtktXNf96huFeN/t9LizlLRqbmGDv\nhS1qtk/BAoGJALULV4/3ekImA36ZXu7KUCZ1qSBWCetgAjcmkFpX6eYckHQBmwiR\nQQGjow3dxNa9wpS5gLhx89Va8ZN5Qk3kzD2do8rPOMDIwOUHWE5fZAm3MBBFOW+D\n7Yj7k188Ik4MJb8ulv6egyFFmfPdVEvg4/BRbRryhimH+2KcaAabEZ/X1/440TUN\naL8CeQD8VrSbyaQmff5i8yXzqXKkILlOFOgkiZ8FBsUcTAzDaAyirde7v2fzh+uT\nU9O1VJXK/nZRkP+IwoXbCYIjKzeWHl6mfjFVmEVuFtfSrUCFLhYq6ON2R5xWsEUD\nMjPuqwcOsd8xNWuCfJL6lq70CN/+E6UhGmAy7gkCgYhG4eDviepBGdcGaxADGAzX\ncfu8oFMT56wWYa/k30TBhm98K+DCMvSrqqC9XhWiKfuT9SkTjfH0l727ip9OFgVt\nHloxnn5O5Iq5YO3PCYQGVcWoqSG6qoGGv1DM2aNowVLKDnipye/3R+Pl2cMWTj+Q\nKKE6CrhCbG4dBrWn2HDHD2AOtbobNlvLAnkAwqksqOWT4THfFXxXcbHtQ1oPOYH9\nV3pnFxyS4HJ2giP5Y2HSg/5zdbYL8FqBfmgjKjbFFcVSq7DMTB34q6LCPedtwuik\nrFBMd1Hd6qNGm7bi2PVRy8QQgft3MbD/yQVc62QiNrbsGfx58iBeFNnn2fxTrcbI\nIWHpAoGJAKkmky0O3KN93AlH0vrDdMKmGz4Jsp0O930EekcX4ocnAwjUNtCENWKY\nkLyjDoAVG1wm9cX3/4poG69VOwMAmnqfOEB0gRy0OBE0jdxGAqi65NY9mBIw7cQl\nUbr+Fl+lazBYrlcSzUbVetrnIlthsfzWJgOmLIzx6GC8R4t8JKE9h+HDW7aKn00=\n-----END RSA PRIVATE KEY-----\n'
>>> key.public
b'ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCydHu7SAK4mVy4dnFHyIOsWE8RvbaORJiVdC2/xXY8Pr7uPCgKmzHSStzLmqYgWCoehFOzcEIbEHdD+mhunwplDgvBcOupLrfQQAxOzbkM45oAOBotx4FbNMvroDCwd01Up4aa0I1NimfFKne6kv+5jETOaV+ZpAosljk/HZnb+A193jlFOEgg9EBAEPIhh3MEaPtf6zUBCUF3xxQgP6cRSY88TPGvQd2V9+zk3hqWpO1+wKTRCnnKY5+qmC5rc459CNwANdcHUbNY3lgxC24hshOILEYq8x2hDM8asu8ak5qkDsorA9cp0ltbuTKFIP3OCf56fdEKXUt8JPlqKEC3'
```