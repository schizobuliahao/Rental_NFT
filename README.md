ERC-4907: EIP-721的扩展——租赁 NFT
向 EIP-721令牌添加具有受限权限的时间限制角色

EIP-721的扩展。一个可以授予地址的附加角色(用户) ，以及一个角色被自动撤销(过期)的时间。用户角色表示“使用”NFT 的权限，但不表示传输或设置用户的能力。


使用场景：
有些 NFT 有一定的实用性。例如，虚拟土地可以用来构建场景，代表游戏资产的 NFT 可以在游戏中用。在某些情况下，所有者和用户可能并不总是相同的。可能有一个 NFT 的所有者把它租给了一个“用户”。“用户”在 NFT 中应该能够采取的行动将不同于“所有者”(例如，“用户”通常不应该能够出售 NFT 的所有权)。在这些情况下，使用单独的角色标识地址是代表“所有者”还是“用户”，并管理相应的执行操作的权限是有意义的。