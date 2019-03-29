# Trends

## Voice interfaces
  - We said it would be a bit crap last year
  - It kinda has been
    - The Alexa creepy laugh story
  - Actually have significant uptake in people's homes now
  - Very country dependent
    - Alexa massive in US, not so much EU
    - Language problems
  - UI
    - Not very clever
    - Voice command line
    - More like voice AppleScript
  - Proximity exploits possible with IoT (e.g. shout "Alexa, unlock the door" through the letterbox)

## Rust
  - Everyone was really excited
  - Anyone using it in prod?
    - Cloudflare maybe? They're excited about it. Not sure if they're using it.
    - Firefox!

## Brexit and legal uncertainty
  - As 2017 notes
  - Still completely uncertain!

## Is gov tech still a thing?
  - Lots of small departments spun out
  - From an outside of government perspective
    - Community leaders have moved on from GDS, not being replaced by new GDS figureheads
  - Used to see a lot of interviewees from GDS, less so now. Have they all left?
  - Remember, there are more departments than GDS!
  - GDS is pushing its vocal tech arm less right now
    - Policy on public speaking/writing is less tech-focused

## Yarn + package managers using lockfiles
  - Lockfiles have won
    - Yarn becoming standardised
    - Go dep has them
    - Pipenv
  - "Having to lock the upper version of a package is something we use as a sign of danger"
    - Updates happening very quickly
    - Tools like Dependabot
      - Cool thing it does: run everyone's tests -> determine compatibility of release
      - i.e. Did this patch version upgrade break everyone's code?

## AWS kube
  - We were cynical, they have announced it!
    - So has everyone else
  - Marketing have launched it, but the tech is behind.
    - The fact that the announcement was at reinvent is because of reinvent, not because the tech was ready

## Kube in general
  - Kubernetes is a concentration of complexity that someone still has to run and manage
    - Maybe this is your cloud provider
  - Has Kubernetes won?
    - Seems so, there are niche cases to run a different orchestrator
    - ECS is also fine
    - So is multi-container EB
  - Kubernetes being converged on by competitors
    - Pivotal platform (Cloudfoundry)
    - Docker themselves support Kubernetes

## ELK security
  - No notable CVEs - roll forward to next year
  - One person exposed it publicly on the internet, got data deleted + ransomed

## Supporting infra on internet
  - Memcached amplification DDoS
  - World read/writable S3 buckets
  - Kubernetes clusters with exposed API (crypto miners)
  - More training wheels from providers?
  - Reckon: major exploit in WASM in next 12 months

## JS crypto miner that got onto a bunch of high-profile sites via compromised central source of JS

## IoT
  - Last year we assumed it would be a problem
    - Focused on who would be legally responsible
  - VW exec jailed for 7 years for emissions cheating

## Software eng union + ethics in software
  - QCon having an ethics track
  - More talk about ethics in the last year!
  - AI
    - Lots of rapid, but unchecked advancement
    - Adversarial attacks against models
    - Use of machine learning to improve attacks against infrastructure
      - Maybe not next year, but it's coming
    - "Machine learning is the buzzword for selling products at _redacted_ that don't work"
      - e.g. "Our firewall now has machine learning!"

# What's new

## "Robotics"
  - Actually just screen scraping
  - Big thing in government, screen scraping old systems that are too expensive to replace
  - Lament: "Crypto and robotics were perfectly good words that meant things"

## The rise of crowd sourcing
  - Expensify story
    - If computer vision doesn't work for receipt scanning, send it to a human

## Attacks against hardware
  - Spectre, Meltdown
    - Rowhammer before them, a precursor?
  - Intel Management Engine

## Trust problems
  - Intel Management Engine
  - Modules on NPM
  - Reckon: someone will, for political reasons, pull an SSL trust chain (e.g. China)

## Regulation of Facebook/social media
  - Facebook implementing "who paid for this ad"
    - People will start to expect to see this
    - This is good
    - Especially if they demand it for political funding
    - Maybe a generational thing

## Flooding attacks on social media
  - Generating (markov chains) tweets that are only detectable as non-human by a human
  - Creating noise to amplify topics

## Prediction: a private company will break out and compete with government branch
  - Already have private companies competing for NHS GP funding
  - Non-TFL buses
  - Similar things have happened before
  - The companies will distort the services in bad ways in search of profitibility
