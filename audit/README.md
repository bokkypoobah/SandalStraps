# SandalStraps Contract Audit

## Summary

<br />

<hr />

## Table Of Contents

<br />

<hr />

## Code Review

* [ ] [code-review/SandalStraps_coll.md](code-review/SandalStraps_coll.md)
  * [ ] contract ReentryProtected
  * [ ] contract OwnedAbstract
  * [ ] contract Owned is OwnedAbstract
  * [ ] interface OwningItfc
  * [ ] interface WithdrawableMinItfc
  * [ ] contract RegBaseAbstract
  * [ ] contract RegBase is Owned, RegBaseAbstract
  * [ ] contract Factory is RegBase
  * [ ] contract Registrar is RegBase
  * [ ] contract RegistrarFactory is Factory
  * [ ] contract Value is RegBase
  * [ ] contract ValueFactory is Factory
  * [ ] contract BytesMap is RegBase
  * [ ] contract BytesMapFactory is Factory
  * [ ] contract Value is RegBase
  * [ ] contract ValueFactory is Factory
  * [ ] contract SandalStraps is ReentryProtected, RegBase, OwningItfc, WithdrawableMinItfc
  * [ ] contract SandalStrapsFactory is Factory