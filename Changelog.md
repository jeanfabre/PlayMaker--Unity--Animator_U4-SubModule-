#PlayMaker Animator Change log

###1.1.0  
**Fix:**  

- *GetAnimatorCurrentStateInfo* action combines Unity 5 api changes into actions to avoid duplicated project maintenance  
- *GetAnimatorIsControlled* action combines Unity 5 api changes into actions to avoid duplicated project maintenance
- *GetAnimatorNextStateInfo* action combines Unity 5 api changes into actions to avoid duplicated project maintenance
- *PlayMakerAnimatorStateSynchronization* action combines Unity 5 api changes into actions to avoid duplicated project maintenance
- *SetAnimatorCullingMode* action refactoring form Unity 5 (AnimatorCullingMode enum changed)

**Improvement:**  

- Using Submodule for Unity 4 and 5 projects

###1.0.1
**Fix:**  

- *SetAnimatorLookAt* now can use AnimatorIK  proxy (apparently MoveIK proxy did nt give the expected [results](http://hutonggames.com/playmakerforum/index.php?topic=10177.msg49090#msg49090))

**Improvement:**  

- ChangeLog and version for Ecosystem compatibility  
- Released on the Ecosystem

###1.0.0
**Note:**  

- Initial Release on [Github](https://github.com/jeanfabre/PlayMaker--Unity--Animator_U4-SubModule-)