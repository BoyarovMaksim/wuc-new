---
layout: post
title: Video - The Essence of How Bitcoin Works Non-Technical
description: Video - The Essence of How Bitcoin Works Non-Technical
author: Melvin Draupnir
authorurl: /melvin-draupnir/
published: true
---

<p>The video is all about the main ideas behind How Bitcoin Works, including how money is transferred, who keeps track of it, and how the whole thing is secured. It also tackles about <a href="/bitcoin-security-standards/">maintaining ledger and keeping transactions safe</a> from foreign intruders. </p>

<center><iframe width="700" height="394" src="https://www.youtube.com/embed/t5JGQXCTe3c" frameborder="0" allowfullscreen></iframe></center>

<h2>TRANSCRIPT</h2>
<p>The goal of this video is to explain the essence of how Bitcoin works without any jargon or scary math.  It is not, however, an introduction to what Bitcoin is or why it matters.  For that, check out the great intro video at Bitcoin.org.  With that said, on to how it works.
<p>Bitcoin lets people exchange money electronically as easily as sending an email or text.  To send money you use what's called a wallet app to type in an amount, enter or scan or recipients account number and hit send.  The recipient will then see the money pop up in their account.  So how does this work?
<p>At a basic level Bitcoin is just a ledger with account numbers and balances.  When Bob sends Carol five Bitcoins, his balance goes down by five and Carol's up by five.  There is no gold or government issued money backing these numbers.  Just people's belief that the numbers are worth something and a system that prevents unfair changes.  Part of the system make sure no one can spend money from someone else's account.  Every time you hit send your wallet app send a message to the Bitcoin network describing how the ledger should change including the senders and recipients account numbers and amount to transfer.  So what's to prevent a thief from creating a message transferring money from someone else's account.  
<p>Bitcoin requires a kind of signature on each message to prove that it was created by the true account owner.  The signature serves the same purpose as a handwritten signature on a paper check but it's based on math rather than handwriting.  The math comes from the world of cryptography which is normally used to hide secret messages.  But in Bitcoin it has been repurposed to prove ownership.  Each Bitcoin account number has an associated key that only the true account owner knows and is used to create signatures by encrypting transaction messages.  Others test the signature by trying to decrypt it.  If successful they know the signature was created by the true account owner.  
<p>In addition to not relying on handwritten analysis this math-based signatures can't be copied and reused on other transactions since the signatures are unique to each transaction.  So these signatures keep unauthorized transactions from changing the ledger.  But who exactly is checking the signatures and overall maintaining the ledger.  Surprisingly, anyone who wants to.
<p>One of the main goals of Bitcoin is to provide a decentralized system.  Meaning no single company or government can control it.  Every time someone sends money, a transaction message is passed around to all the people who want to help maintain the ledger who I'll call maintainers.  Each maintainer keeps a personal copy of the ledger and updates it whenever they receive a new transaction with a valid signature.  With ledger spread all over the world, traffic delays and occasionally fraud can lead to differences in those ledgers.  So how does the world decide which version to use.  
<p>Like another democratic system there is a vote but it's a bit different than a typical ballot system.  Maintainers vote by trying to solve a special puzzle based on their version of the ledger.  The first person to solve a puzzle announces their solution and everyone updates to that version.  So, the vote turns out to be a kind of mathematical race but it's designed to favor the majority's version.  This is because the more people there are working on a particular version the faster it will be solved.  Because new transactions are constantly being generated this voting process repeats over and over again so maintainers can continually agree about new transactions.
<p>So why math problems instead of say emailing in votes to decide on a ledger?  Without a central authority to register voters it would be hard to enforce one vote per person.  A single person could create multiple accounts to vote more than once or even millions of times.  The math problems prevent this by making each vote have a cost in computers and electricity.  This means out voting or out solving the majority to take over the ledger would effectively require outspending the majority, an unlikely event.  So the math enables a fair vote in a decentralized system.
<p>Two more important details about how it does this.  To prevent someone from pre-solving the puzzle to win the race each puzzle builds on previous answers and the winner is not just the most recent solution but the ledger version with the most total solutions.  The puzzles are also extraordinarily special and that there are no tricks to solving them faster other than by buying more computers and electricity.  It's this property that underlies the entire system and gives people assurance that the solutions are truly from the majority and not a clever attacker.
<p>A final note about how money is created.  Every time a puzzle is solved a small award is added to the solvers balance effectively creating money out of thin air.  This award acts as an incentive for people who help maintain the ledger and is in addition to small fees senders attached to transactions.  Because maintainers acquire newly created money through computation they are typically called miners.  But their main purpose is really to manage the ledger, not to create money.  The voting system simply provides a convenient way to randomly distribute money into the world and in fact after 2140 no more money will be created.
<p>In some rate, Bitcoin is an electronic currency that's based on a collaboratively maintained ledger.  People transfer money by sending messages to maintainers describing where and how much money should move.  Maintainers make sure that the messages are from the true account owners by checking digital signatures.  And finally, the maintainers reach consensus with each other through a math-based voting process.  I hope this gives you a quick sense for how Bitcoin works.  If you'd like to dive deeper into the rabbit hole, check out my 22-minute video, How Bitcoin works under the hood.  Also feel free to subscribe for more concise tech explanations.