## Implementation of off-chain signing (EIP-712) to permit a Uniswap swap

### Goal:
--To allow a user to approve & execute a Uniswap swap using an off-chain EIP-712 signature instead of a prior on-chain approve transaction.
--The flow allows a relayer or the user to submit the signed permit and perform the swap in a single on-chain transaction.
