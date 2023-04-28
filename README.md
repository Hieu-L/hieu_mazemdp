# Hieu's MazeMDP

This is a custom library taken from Mr. Olivier Sigaud's SimpleMazeMDP library, with modifications to remove the "well" state.

The "well" state was a state that any actions from the final state (state containing a reward) would lead to. The reward would then be received upon taking the transition :  final state  ---action--->  well state .

I modified the library to remove the well state, so that the reward would be received by taking any transitions that would lead to the final state :  ___  ---action--->  final state.


I've been using this custom library to work on my research project on Priotized Replay algorithms, to create a discrete maze environment as well as an agent to navigate it. 

For any and all inquiries, feel free to contact me through my email! ==> hoang.hieu.le212@gmail.com
