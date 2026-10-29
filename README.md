# word-break
Uses Dynamic Programming. dp[i] is true if prefix s[0...i-1] can be segmented. We iterate through each index i and check all split points j. If dp[j] is true and the substring from j to i exists in the word dictionary, dp[i] becomes true.
