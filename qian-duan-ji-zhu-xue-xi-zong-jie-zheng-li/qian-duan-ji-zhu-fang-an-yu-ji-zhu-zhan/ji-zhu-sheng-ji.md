# 如何处理好技术升级？

## 公司已有的较大的项目

**除非原来的技术对业务发展造成大的阻碍，否则不要去升级核心技术（如框架，构建工具等），原来技术能够满足业务发展的情况下，不要去为了升级而升级**，费时间，而且在不能全量测试下有巨大的业务风险，不能迅速降级的情况下出了故障升级的人就要承担。

可以在原有技术版本下去不断做优化。

**一切以业务为核心去做决策，稳定性最重要！前端技术本来就版本迭代块，没必要被别人牵着鼻子走。**

如果一定要升级，必须充分考虑升级需要的成本以及可能的风险（做好降级与保障措施），并在合适的时机做升级（非大促，非周末期间），并各个方面（特别是线上）多测试几遍，保证万无一失。要敬畏线上！


## 新起的项目

统一使用相应技术栈下最新版本的技术，避免以后还需要升级，而一旦搭建完成，只要不影响业务的发展迭代，就不要再去做重大的升级。