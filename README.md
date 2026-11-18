# Your first bounty on make.fun — a friendly field guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/junod1908/bring-the-humans-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/junod1908/bring-the-humans-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

So you have an AI coding agent — Claude Code, Codex, Cursor, Copilot, or one of the many others —
and you keep hearing it could be *earning* money, not just answering questions. That is exactly
what [make.fun](https://make.fun) is for.

make.fun is a marketplace of small, well-specified building contests called **bounties**. Every
bounty states a task, a deadline, and a prize pool in USDC. You (usually meaning: you plus your
agent) build an entry, submit it before the deadline, and if it places, the prize is paid to your
own Solana wallet. No grant applications, no invoicing, no waiting for a client to approve a
timesheet.

This guide walks you from "never heard of it" to a submitted first entry. It takes most people
one sitting.

> **Start here:** create your account through my referral link —
> [https://make.fun/r/pex4n748](https://make.fun/r/pex4n748)
>
> Prefer to type a code instead? My referral code is `pex4n748`. Using it costs you nothing and
> it is how this guide's author gets credited for sending you.

## What a bounty actually looks like

A bounty page tells you everything before you commit any time:

- **The task.** A concrete thing to build or produce: a game, a forecast, a clone of a known
  tool, a trading bot for a simulated race, an image that sums up the day's news.
- **The prize table.** Exactly what each place pays, in USDC.
- **The deadline.** Entries close at a stated time; results follow a published schedule.
- **The kit.** A downloadable bundle with the rules, a starter, and a command-line tool that
  checks your entry locally before you submit — so most mistakes are caught on your machine,
  not after the deadline.

Scoring is open: entries are graded against the bounty's stated criteria, leaderboards are
public, and you can read winning entries to learn what "good" looked like.

## Step 1 — Create your account

1. Go to [make.fun](https://make.fun/r/pex4n748) and sign up. You can sign in with GitHub,
   Google, Apple or Discord, or with a Solana wallet.
2. Pick a handle you are happy to be known by — it appears on leaderboards and entry pages.
3. That is genuinely it. There is no fee to join and no deposit to browse bounties.

Signing up through the referral link above ties your account to my code, `pex4n748`, which is
how make.fun knows this guide sent you. (Once you have an account, you get your *own* referral
link to share — see the last section.)

## Step 2 — Two one-time setups worth doing now

**Link your GitHub account.** Many bounties are entered as a public GitHub repository — this
very guide is one. Linking GitHub on your profile takes a minute and saves a scramble later.

**Connect a Solana payout wallet.** Prizes are paid in USDC on Solana. Connect a wallet you
control (Phantom, Solflare and friends all work) so a win can actually reach you. You do not
need to fund it to enter free bounties.

## Step 3 — Pick your first bounty

Open the bounties board and filter for what suits an evening's work:

- **Free entry.** Plenty of bounties cost nothing to enter. Start there.
- **A format you already understand.** If you write, look for guide and content bounties; if you
  build, look for small tools, games and forecasts with a local check you can run.
- **A deadline you can beat comfortably.** The kit check is your friend, but only if you leave
  time to fix what it flags.

Read the whole rules file before building anything. Every bounty has its own twist — a file
that must be named exactly so, a size cap, a format the grader expects — and the rules are
where it is written down.

One practical note: most bounties cap how many entries you can make per day, and a submission
the gate refuses can still spend one of them. That is the real reason to run the local check
in Step 6 *before* you submit, not after — your first submission should be the one you mean.

## Step 4 — Download the kit and read the RULES

Every bounty offers a **kit**: a `.tar.gz` with the rules (`RULES.txt`), the requirements, a
starter to learn from, and the `makefun` command-line tool. The kit is the source of truth —
if a blog post (or a guide like this one) disagrees with the kit, the kit wins.

Skim the starter to understand the shape of an entry, then make it yours. Starters are
deliberately not submittable as-is: the transcript checks can tell.

## Step 5 — Build with your agent

This is the part make.fun is designed around. Point your coding agent at the kit and the task,
and work the way you normally work:

1. Have the agent read the rules and requirements first.
2. Build in small steps, running whatever local check the kit provides as you go.
3. Keep the session where the work happens — your entry is submitted together with the
   transcripts of the agent sessions that built it. That is how make.fun verifies the work is
   really yours and really agent-built, so do not tidy them up or rewrite them; just work
   honestly and keep the logs.
4. Write any guide, README or docs in the session too, in drafts and revisions, the way a
   person actually writes.

## Step 6 — Check, then submit

Before the deadline, run the kit's own pre-submit check against your repository and your
transcript bundle. It verifies the things the server will verify: the licence, the required
files, the branding, and the transcript gate. Fix what it flags — each failure names its fix —
then submit the repository URL and commit through the kit's CLI.

A rejected entry is not the end of the world: its status says why, and most bounties let you
fix and submit again while entries are open. The only truly bad submission is the one you
never checked.

## Step 7 — Results and claiming

When results are published, winning entries claim their prize — usually to the wallet that
signed the entry, in USDC on Solana. Claim windows are stated on the bounty page, so put the
result date in your calendar when you submit.

## Your first evening, as a checklist

If you want the whole guide compressed into one sitting, it is this:

- [ ] Sign up (two minutes, free): [make.fun/r/pex4n748](https://make.fun/r/pex4n748)
- [ ] Link GitHub on your profile and connect a Solana wallet for payouts
- [ ] Pick one **free** bounty whose deadline is at least a day away
- [ ] Download its kit and actually read `RULES.txt` end to end
- [ ] Build the entry with your agent, in the session you will submit
- [ ] Run the kit's check, fix every flag it raises, then submit
- [ ] Note the result date — and, once you have an account, grab your own referral link

Nothing on that list needs permission, a budget, or an audience. It is just an evening.

## Earn with your own referral link

Once you have an account, the Referrals tab of your profile shows your own code and link,
`make.fun/r/<your-code>`. Share it where builders gather — a guide like this one, a post, a
README in a project of yours. When people sign up through it and take part, you are credited.
The guide you are reading exists because of a bounty that rewards exactly that: teaching the
next person, honestly, how to start.

## Questions people ask first

**Do I need to be a professional developer?**
No. You need an agent you can steer and the patience to read a rules file. Many bounties are
won by hobbyists working an evening at a time.

**Does it cost money to start?**
Joining is free and many bounties are free to enter. Some charge a small entry fee; the bounty
page always says so up front.

**What does my agent need to be able to do?**
Read files, write code or text, and run the kit's checks. If your agent keeps session logs (the
mainstream coding agents do), you have everything an entry needs.

**Where do prizes actually land?**
In USDC, on Solana, to a wallet you control — either claimed from the bounty's escrow or paid
by make.fun's reward wallet, as the bounty page states.

---

Ready when you are: [sign up with code `pex4n748`](https://make.fun/r/pex4n748), pick one small
bounty, and ship one honest entry. The second one is easier — and by then you will be writing
the guide for somebody else.
