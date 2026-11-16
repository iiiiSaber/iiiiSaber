
## Welcome!

He’s a master’s student at Xidian University,
exploring AI agents, systems, and algorithms.

Outside of code, he enjoys mathematics, literature, and anime.

See more about me: [my blog](https://isaber.top).

## Inspiration
A snippet of code you may be interested in:

```cpp
using ll = long long;
constexpr ll P = 998244353;

ll inverse(ll a) { // 0 < a < P
    ll result = 1;
    for (ll n = P - 2; n; n >>= 1) {
        if (n & 1) result = result * a % P;
        a = a * a % P;
    }
    return result;
}
```


