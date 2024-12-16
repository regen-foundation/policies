Alexander | P2P Validator — 12/13/24, 10:54 AM
So, here is our main script - https://drive.google.com/file/d/1G9ovii7fi-rtucBLyeCkjgdTJ6kA_udH/view?usp=sharing
There is a part somewhere in the middle - https://colab.research.google.com/drive/1G9ovii7fi-rtucBLyeCkjgdTJ6kA_udH#scrollTo=dc592d9c52d7a722&line=1&uniqifier=1
which requires some manual collection for uptime data (we used to get it from Mintscan, but it stoped working at some point).
Here is a separate script to collect block data to calculate uptime - https://drive.google.com/file/d/1GdwRYrq9nQwg_pGjTdQo7VnBDxLkc3lH/view?usp=sharing
There might be some RPC endpoints used in there that might need replacing, since they can only be accessed from within our company infra.

I hope this will be at least somewhat helpful. Our analyst said that he'd just do that from scratch if he was in your shoes, but happy to support you if you want to use our stuff!
