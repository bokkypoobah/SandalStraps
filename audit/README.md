# SandalStraps Contract Audit

## Summary

<br />

<hr />

## Table Of Contents

<br />

<hr />

## Code Review

* [ ] [code-review/SandalStraps_coll.md](code-review/SandalStraps_coll.md)
  * [x] contract ReentryProtected
  * [x] contract OwnedAbstract
  * [x] contract Owned is OwnedAbstract
  * [x] interface OwningItfc
  * [x] interface WithdrawableMinItfc
  * [x] contract RegBaseAbstract
  * [x] contract RegBase is Owned, RegBaseAbstract
  * [ ] contract Factory is RegBase
  * [ ] contract Registrar is RegBase
  * [ ] contract RegistrarFactory is Factory
  * [ ] contract BytesMap is RegBase
  * [ ] contract BytesMapFactory is Factory
  * [ ] contract Value is RegBase
  * [ ] contract ValueFactory is Factory
  * [ ] contract SandalStraps is ReentryProtected, RegBase, OwningItfc, WithdrawableMinItfc
  * [ ] contract SandalStrapsFactory is Factory