Early troll prediction (RE: Hacker Noon announcement): "Everybody will leave Medium in a year"

# From last year

## Smarter viruses that don't kill the host
  - Better to mine cryptos than cause damage
  - They're no quieter than they were last year though

## SWE Ethics to become a hot topic (especially machine learning)
  - Still seems to be growing, but no major change since last year

## Social media regulation
  - It's happening slowly
  - "It's coming along at the pace that regulation does"

## More attacks against hardware

## Private companies competing with branches of government
  - Citymapper now has an Oyster competitor

## Voice interfaces
  - Anyone using it in the office yet?
    - e.g. "Alexa deploy to produciton"
    - Nobody has heard of anyone doing this
  - Alexa Skills are a use case for serverless
  - Bad for people called Alexa
  - UI still a bit crap

## Kubernetes
  - All the cloud providers now have it
  - Seems to have won the container orchestration war
  - By show of hands in room
    - Most people aren't using it, of those who are:
      - Most use a managed one run by a cloud provider
      - Fewer people run it themselves

## `dep` seems to be winning the Go package management wars
  - Not any more!
  - Now we have vgo instead
  - Still has lockfiles, which we said had won in package managers in general

## CI
  - People still mostly using Circle, Jenkins
  - Buildkite growing in popularity
  - Concourse also seeing some use
    - Even from people not involved with Cloudfoundry!
  - RIP Travis
    - "Embraced and extended"
    - People moving away, unhappy at how developers were treated post-acquisition
      - Maybe not the best PR move if you're a company running a service aimed at developers
    - Anecdotally, service seems to be getting worse
  - Anyone using GitHub actions?
    - At least one person using it as a CI replacement, and not just simpler "delete branch on merge" actions
  - Jenkins X
    - Container-native Jenkins
    - A bunch of Kubernetes tooling glued together
    - Debate over whether it has continued momentum/backing

## ELK security
  - If you leave it all open to the internet someone will get the data
  - Also happening with Mongo
  - Not new in either case this year, just continued

## Supporting infra on internet being attacked
  - Getting worse
  - Shodan effect
    - There are aggregators/collators of list of specific resources you might want now
  - Fuzzing happening more?
    - Maybe this was there anyway
    - Google Project Zero a vocal example
    - More tools available (NSA open sourced a thing, though maybe more aimed at reverse engineering?)

# What's new this year

## Everyone's doing Rust
  - "You said that last year!"
  - WASM is interesting
    - "We said that last year too!"
    - Cloudflare and Fastly have released products that let users run it at the edge
    - Companies trying to push edge computing more now
      - "The future of serverless?"

## Serverless
  - Anecdotes of people trying it then moving off when they realise it's not right for them
  - It's hit full buzzword status
    - Non-technical people asking "What's our serverless strategy?"
  - No track at QCon
    - Thought: Having a track at QCon can be an indicator of success with the group who come in just after early adopters

## Kubernetes
  - Federation becoming really good
    - Could lead to easier multi-cloud setups
  - Prediction: remote builds in different server farms
    - [Ed: I wasn't sure what this was referring to]

## Typescript on the server
  - Linked with uptake of strongly typed languages in general
  - Node is already super popular, and so Typescript is an easy way into types
  - "On the infra side we've moved to Go"
    - People agree with this
    - [Conversation turns to trolling]
      - "No, we've moved to YAML!"
        - Awkward nodding
      - "If you're building something in Rust you have to tell everyone"
        - "It's the crossfit of languages"

## Microsoft bought GitHub
  - Puts Gitlab in a different position
    - "They'll get bought by Google"
  - People broadly still using GitHub post-acquisition (contrast Travis above)
    - Actually easier to buy GitHub as a government dept now as they recognise Microsoft

## Conversations around open source licensing
  - Suddenly cool to talk about again
    - "Well..."
  - Driven by cloud providers and use of FOSS, charging for the service based on it
  - Both sides have commercial reasons to dislike the other side
  - Will it resolve itself quietly or will it cause us all issues
  - In many cases cloud providers implement at a wire-compatibility level
    - Oldest trick in the book: Word became popular because it could read WordPerfect files
    - That's slightly different
      - You're still aware you're using different software, with wire-compatible you don't know what's behind it
  - Prediction: no company will release an open-source database in 2019
    - i.e. No CockroachDB model
    - Maybe that means no new databases? Can things like Cockroach launch without that open source version?
    - Maybe more "source available" databases when you've signed a contract
      - [Ed: specific recent example was given here, missed taking note of it]
  - Will we see a new iteration on the AGPL?
    - Or will people standardise around one of the ones drafted recently (e.g. RedisLabs one)
    - But if cloud providers copy the wire protocol you're still screwed

## Changes to AU law requiring backdooring
  - Some people asking not to build datacentres in AU
  - What about Atlassian software?
    - Some examples of companies moving off
      - Change of law was one factor, but not the only one

## Observability
  - Lots of talk this year
  - As opposed to standard monitoring
  - Is it actually that different to what we've been doing?
  - Better adoption of structured logging because of the focus on events
  - More standards emerging

## People being surprised by cloud bills of companies going public
  - Lyft was recently in the news
    - 22c per ride going to that bill
    - "Doesn't seem that bad on a $6 ride"
