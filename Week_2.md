# Week 2
### Goals

1. Use all of week 1's skills (don't underestimate the importance of this)
2. Break one class into two classes that work together, while maintaining test coverage
3. Unit test classes in isolation using mocking
4. Explain some basic OO principles and tie them to high level concerns (e.g. ease of change)
5. Review another person's code and give them meaningful feedback

#### Evidence

1. Explore_Game [week1](https://github.com/RaeRachael/exploration_game#friday-15th-may),[week2](https://github.com/RaeRachael/exploration_game#friday-22nd-may)
2. Journey in Oystercard, Formatter in weekend takeaway
3. [Explore_Game](https://github.com/RaeRachael/exploration_game/tree/master/spec), [Airport](https://github.com/RaeRachael/airport_challenge/tree/master/spec), [Oystercard](https://github.com/RaeRachael/Oystercard/tree/master/spec), [Take-away](https://github.com/RaeRachael/takeaway-challenge/tree/master/spec)
4. xplore_Game [week1](https://github.com/RaeRachael/exploration_game#friday-15th-may),[week2](https://github.com/RaeRachael/exploration_game#friday-22nd-may)
5. [Review of Al's Airport](https://github.com/makersacademy/airport_challenge/pull/1811) and Review of Sophie's Airport (Pull request has been closed)

### Daily Goals

#### Monday 18th May

goal: continue working on comunication while pairing <br/>
plan: get feedback during the pairing session on this <br/>
evidence: the conversations. <br/>
proof: no-one seems very annoyed at me yet :) (very much sarcasm)

#### Tuesday 19th May

goal: gain insight into good design practice. <br/>
plan: Domain modelling workshop, going over the exploration_game with coach. <br/>
evidence: having a better process for designing code, having ideas of how to show the design of explore game more clearly. <br/>
proof: only a few scribbled sketches - a better picture should be in the README.md of explore_game by next week, [week1](https://github.com/RaeRachael/exploration_game#friday-15th-may)

#### Wednesday 20th May

goal: to the ideas I read about for encapsulation into practice, and the further practice different ways to test in RSpec, trying to find good ways to test behaviour over state. <br/>
plan: keep appropriate tabs open in chrome to check while building tests and looking at the layout of the methods in each class. <br/>
evidence: finish the spec tests for Tile classes in explore_game, then begin to refactor the code via private methods.<br/>
proof: state of the exploration_game, [Tile spec tests](https://github.com/RaeRachael/exploration_game/tree/master/spec/tiles)

#### Thursday 21st May

goal: to the ideas I read about for encapsulation into practice, and the further practice different ways to test in RSpec, trying to find good ways to test behaviour over state. <br/>
plan: keep appropriate tabs open in chrome to check while building tests and looking at the layout of the methods in each class. <br/>
evidence: finish the spec tests for feature responses in explore_game, then begin to refactor the code via private methods<br/>
proof: state of the exploration_game [feature tests](https://github.com/RaeRachael/exploration_game/tree/master/spec/feature_tests)

(exciting event - first time I used an exit code. For testing that the game exits at a certain point (monster-player in the same location)
(exciting event - creating error class to handle level changes and so that stairs can be tested)

#### Friday 22nd May

goal: to understand how to make a custom error class, and to be about to access the messages in it. <br/>
plan: look up more examples of custom classes, find documentation of the code for sub classes of StandardError <br/>
evidence: both the code and the tests run correctly at the same time.<br/>
proof: state of the exploration_game; [stairs up spec](https://github.com/RaeRachael/exploration_game/blob/master/spec/tiles/stairsup_spec.rb), [stairs down spec](https://github.com/RaeRachael/exploration_game/blob/master/spec/tiles/stairsdown_spec.rb), [#tile_interaction in interface](https://github.com/RaeRachael/exploration_game/blob/master/lib/interface.rb)

updated [exploration_game README.md](https://github.com/RaeRachael/exploration_game/blob/master/readme.md)
