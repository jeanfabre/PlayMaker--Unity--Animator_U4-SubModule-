#PlayMaker Animator Change log

###1.1.6
**Released:** 05/05/16  

**Fix:** Fixed `SetAnimatorIKGoal` don't know it got corrupted..

###1.1.5
**Released:** 04/05/16  

**Fix:** Fixed `PlayMakerAnimatorStateSynchronization` compatibility with PlayMaker 1.8 in Unity 5+

###1.1.4  
**Released:** 04/05/16  

**Improvement:** Added EveryFrame Option to animatorPlay to animate time  

**Update:** Update to latest PlayMaker Utils submodule  

###1.1.3
**Fix:** fixed all actions using OnAnimatorIK to not fire warning ( can't use Update anymore)  
**Update:** updated PlayMaker Utils submodule  

###1.1.2
**Update:** Update to latest PlayMaker Utils  
**Fix:** Fixed `PlayMakerAnimatorStateSynchronization` compatibility with PlayMaker 1.8  

###1.1.1
**New:** *PlayMakerStateMachineBehaviorProxy* to be dropped directly onto an Animator State to fire events when animator state is entered or exited  

###1.1.0  
**Fix:** *GetAnimatorCurrentStateInfo* action combines Unity 5 api changes into actions to avoid duplicated project maintenance   
**Fix:** *GetAnimatorIsControlled* action combines Unity 5 api changes into actions to avoid duplicated project maintenance  
**Fix:** *GetAnimatorNextStateInfo* action combines Unity 5 api changes into actions to avoid duplicated project maintenance  
**Fix:** *PlayMakerAnimatorStateSynchronization* action combines Unity 5 api changes into actions to avoid duplicated project maintenance  
**Fix:** *SetAnimatorCullingMode* action refactoring form Unity 5 (AnimatorCullingMode enum changed)  

**Improvement:** Using Submodule for Unity 4 and 5 projects  

###1.0.1
**Fix:** *SetAnimatorLookAt* now can use AnimatorIK  proxy (apparently MoveIK proxy did nt give the expected [results](http://hutonggames.com/playmakerforum/index.php?topic=10177.msg49090#msg49090))  

**Improvement:** ChangeLog and version for Ecosystem compatibility  
**Improvement:** Released on the Ecosystem

###1.0.0
**Note:** Initial Release on [Github](https://github.com/jeanfabre/PlayMaker--Unity--Animator_U4-SubModule-)  