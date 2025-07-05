def palindrome(t):
    t = t.lower().replace(" ", "")
    m = len(t)
    for i in range(m // 2):
        if t[i] != t[m - i - 1]:
            return False
    return True

t = 'Cfas afc'
if palindrome(t):
    print("YES")
else:
    print("NO")


    def transpose(m,n,arr):
  arr2 = [[10 for i in range(m)] for j in range(n)]
  for i in range(m):
        for j in range(n):
            transpose[j][i] = arr[i][j]

  return arr2

  import yfinance as yf
import matplotlib.pyplot as plt
stock= yf.Ticker("MSFT")
stock
data_historical = stock.history(start="2023-01-01", end="2024-01-01")
data_historical
