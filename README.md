Cycle.js Android
=========

A Proof of Concept that tries to port the [Cycle.js](http://cycle.js.org) reactive concepts to Android.
It currently uses [Anvil](https://github.com/zserge/anvil) for incremental UI updates, [Retrofit](https://github.com/square/retrofit)
for HTTP requests and, obviously, [RxJava](https://github.com/ReactiveX/RxJava) for the Observables
implementation.

It's still very early stage and far from usable, but demonstrates how that can be achieved.
The repository has a sample app with 3 demos: The classic hello world, counter and Github search.
All have been ported from the Cycle.js [Examples repository](https://github.com/cyclejs/examples).

This is for now just a proposal and I'm hoping to get feedback from people before investing more time
on it.


License
-------

    Copyright (C) 2016 Felipe Lima

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



