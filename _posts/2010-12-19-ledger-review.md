---
layout: post
title: Ledger Review
description: A review of the Ledger Bitcoin wallet.
toc:
  basics: The Basics
  security: The Security Concept
  display: Security card in lieu
  using: Using the device
  installing: Installing the Ledger
  wallet: Using the wallet
  pros: Pros
  cons: Cons
  conclusion: Conclusion
---

<p>A quite affordable hardware for bitcoin called <a href="http://geni.us/ledger">Ledger Wallet Nano</a> has a handful of brilliant hacks up its sleeve. The look is good and promised to be improved by the company withan accompaniment mobile app planned to be released in 2015.  </p>
{% include page-toc.html %}
<p><center><img src="/images/ledger-wallet-1.jpg" alt="Ledger Wallet Review"/></center></p>

<h2 id="basics">The Basics</h2>

<p>This Ledger Wallet Nano lists among newly <a href="/blog/">hierarchical deterministic multisignature hardware wallet</a> for users of bitcoin which targets to eliminate several attack vectors using a second layer of security. To an average customer, this description is too technical so it doesn’t really mean much to them, that’s why I’m gonna explain it in simple terms, defining what causes this Ledger Wallet Nano click. </p>

<p>It was early December when this wallet was launched, and for more project background, don’t hesitate to watch our launch coverage.</p>

<p><center><img src="/images/ledger-wallet-2.jpg" alt="Ledger Wallet Review"/></center></p>

<p>Talking about the hardware, this kind of ledger wallet is a solid USB device based on a microchip. Its size is roughly the same with a small flash drive, which measures 13 x 39 x 4 mm (0.51 x 1.53 x 0.16 in) and weighs just around 5.9g. </p>

<p><center><img src="/images/ledger-wallet-3.jpg" alt="Ledger Wallet Review"/></center></p>

<p>It comes with a box that holds a recovery sheet, a simple manual and also a security card in black pouch made with faux leather. </p>

<p><center><img src="/images/ledger-wallet-4.jpg" alt="Ledger Wallet Review"/></center></p>

<p>I don’t have any major complaints with regards to the <a href="/best-bitcoin-exchanges/">physical quality</a>, though there are some visible rough edges upon closer examination. Just like a typical USB drive, it has a swivel cover made in aluminum with a brushed texture. As a matter of fact, the design resembles strangely the same to a series of flash drives named Super Talent’s Pico-A.</p>

<h2 id="security">The Security Concept of Ledger Wallet Nano</h2>

<p>Ledger Wallet Nano and the traditional USB’s similarities end with the former’s familiar design. The Ledger is considered more reliable since it doesn’t use low-cost NAND memory like an average USB drive. The EEPROM memory manufacturer employed in the compliant smartcard named CC EAL5+ gives out a 30-year assurance on retention of data and five hundred thousand read or write cycles. </p>

<p><center><img src="/images/ledger-wallet-5.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The smartcard was considered for decades an industry standard and eradicates several security issues that will possibly arise on such devices established on multipurpose microcontrollers. </p>

<p>Obviously not made as a device that stands alone, the wallet relies on the main computer to set up and perform transactions. With the host computer as the most possible point of failure, this device is constructed to provide susceptible as well as compromised computers by presenting a new layer of security. </p>

<p>Bitcoin transactions are signed by the wallet internally and targets to avoid MITM or man-in-the-middle attacks by using a security card. If the added security layer is absent, it makes the wallet susceptible to MITM attacks, in which a hacker could theoretically gain command of the computer as well as proceed to damage the wallet. The security card provides a physical authentication which is a two-factor making such attack less likely. </p>

<p><center><img src="/images/ledger-wallet-6.jpg" alt="Ledger Wallet Review"/></center></p>

<p>Without human interaction, it’s impossible for a transaction to be signed so each transaction needs the user to scrutinize the security card visually upon the wallet app’s cue. The wallet shows the fee address so it will require the user to type in codes of the address in four random parts. If you are unable to enter a right code, no transaction can take place. </p>

<h2 id="display">Security card in lieu of dedicated display</h2>

<p>As we have reviewed for the past few months, the hardware <a href="/coinbase-review/">wallet called Trezor uses a screen</a> to address this problem, enabling users to type in the PIN using a numberic pad in pseudo-random, only seen by the user. The team of Ledger chose a different kind of approach which is in a security card form with characters in 58 pairs.  </p>

<p>The basic concept is the same, however what’s different is the implementation. Using a card in front of a screen certainly gives way for a device which is smaller and tracks down the overall cost.</p> 

<p><center><img src="/images/ledger-wallet-7.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The deal is that it likewise results in possibly lesser combination of the code which is the second-factor. A determined attacker with full control over the PC of the user could theoretically reorganize the security card following numerous transactions. Every transaction gives the attacker more ‘depth’ until enough information is composed to totally map and reorganize the security card’s contents.</p>

<p>It may sound weird but using the wallet in several different PCs ridden with malware would theoretically be safer from the perspective of an anti-MITM than employing to do a number of transactions in your personal computer. </p>

<p>Knowing these limitations, Ledger is working to <a href="/localbitcoins-review/">make a companion app</a> in mobile that will basically allow other device for the wallet as a screen. The app is to be paired using the security card into the wallet, granting the wallet to exhibit the challenge on this mobile device, in accordance with the amount of BTC and target address.  The security challenge can now be signed by the user and will facilitate the transaction. This companion app is planned to be released by the company in January 2015.</p>

<p>Ledger is aware of these limitations and is working to develop a mobile companion app that will essentially allow another device to act as a screen for the wallet. The app will be paired to the wallet.</p>

<h2 id="using">Using the device</h2>

<p><center><img src="/images/ledger-wallet-8.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The wallet is formed for desktop operating systems use on the Google Chrome’s browser. I decided to use an Asus tablet as a test bed which was a Windows 8.1 plus its keyboard dock. </p>

<h2 id="installing">Installing the Ledger Wallet Nano</h2>

<p><center><img src="/images/ledger-wallet-9.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The process of installation is somewhat straightforward, but it requires using a Google Chrome app. The Ledger wallet should just be plugged in by the user into the USB port then goes over to my.ledgerwallet.com in order to install automatically the Chrome application that gives access to blockchain by connecting to the Ledger’s API server. </p>

<p><center><img src="/images/ledger-wallet-10.jpg" alt="Ledger Wallet Review"/></center></p>

<p>Although relatively famous, Chrome isn’t the only browser used on the market since <a href="/coinmama-review/">millions still use Safari</a>, Firefox as well as Internet Explorer. An approach which is platform-agnostic may have been preferred, but for several reasons which include security certificates is simply unfeasible. Linux users should as well make a group of udev rules in order to allow entry to the device.  </p>

<p>By the time this app is ready, you will then be prompted to type in the PIN. The PIN can be chosen by the user or the user can opt to use the one that the installer suggested. Then appears the recovery seed, upon the wallet’s initialization where it generates a mnemonic seed which is 24 words and must be stored favorably on the recovery sheet included.  </p>

<p><center><img src="/images/ledger-wallet-11.jpg" alt="Ledger Wallet Review"/></center></p>

<p>Displayed only once, the seed should not be kept on your PC, in digital form. It is the only way the wallet will be restored in case of hardware failure or loss. It can be accomplished with the use of a Ledger wallet replacement, but the procedure as well works on Electrum which is an alternative BIP39 wallet.</p>

<p><center><img src="/images/ledger-wallet-12.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The initialization of the Ledger Nano should be done using an uncompromised computer. One method of executing this is through an air gap, with the use of live OS just like Chromium in a USB stick, which should not consume a lot of time, although it involves a bit tinkering of BIOS (i.e. boot sequence changing).</p>

<p><center><img src="/images/ledger-wallet-13.jpg" alt="Ledger Wallet Review"/></center></p>

<p>Aside from the 24-word restoration phrase, the recovery sheet which is neatly arrange includes the recovery QR code of the security card which can be utilized in case of theft or loss to make a brand new copy of the 2FA. If you entered the PIN mistakenly for three times straight, the wallet will automatically self-reset to default factory condition. This can also be a procedure used to wipe out the device in case you need to sell or give it. </p>

<h2 id="wallet">Using the wallet</h2>

<p><center><img src="/images/ledger-wallet-14.jpg" alt="Ledger Wallet Review"/></center></p>

<p>By the time the installation is done, the user needs to simply insert the wallet into a USB hub and type in the PIN to start accessing the wallet. </p>

<p><center><img src="/images/ledger-wallet-15.jpg" alt="Ledger Wallet Review"/></center></p>

<p>But, all transactions need validation by the use of the <a href="/indacoin-review/">security card</a>. The wallet will give a challenge first. Next, the user should follow instructions and then type in the four-character key to allow transaction validation. This is completed by entering the matching characters from the card.</p>

<p><center><img src="/images/ledger-wallet-16.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The wallet is just easy to use itself and you can feel at home if you’re already familiar with the bitcoin wallets. What’s different is only the additional validation layer with the use of security card. Luckily, the whole procedure is fast and simple which only takes less than 20 secs per transaction.</p>

<p><center><img src="/images/ledger-wallet-17.jpg" alt="Ledger Wallet Review"/></center></p>

<p>The wallet additionally highlights a QR scanner. In spite of the way that QR examining has restricted applications on desktop stages, I utilized it to reproduce besting up a versatile wallet and it worked fine. It could be a significant help in a few circumstances. </p>

<p>By and large there is very little to say in regards to the wallet – and this is something worth being thankful for – it's pretty much a customary bitcoin wallet with an additional layer of validation, which doesn't take up a ton of time. </p>

<h2 id="pros">Pros</h2>

<p>Extremely minimized and smooth outline. The Ledger can fit on any keychain, yet keep in mind the security card. </p>

<p>Esteem for cash – at €29.90 the Ledger Wallet Nano is fairly shoddy to the extent equipment wallets go. </p>

<p>The utilization of a smartcard in lieu of broadly useful microcontroller ought to lift security and dependability over the long haul </p>

<p>Approval by means of security card does not require a ton of exertion or time </p>

<h2 id="cons">Cons </h2>

<p>The gadget must be introduced on a consummately safe PC and not each client will be quick to utilize the 'air hole' approach. </p>

<p>The security card approach has its own <a href="/best-bitcoin-exchanges/">particular upsides and downsides</a>. While it holds the cost down and permits creators to make a genuinely pocketable gadget, it additionally gives somewhat bring down levels of security than a gadget with a devoted screen. Be that as it may, this issue could to some degree be tended to by the up and coming friend application. </p>

<p>Can't be utilized on cell phones, support is at present constrained to Chrome program. </p>

<h2 id="options">Options </h2>

<p>The Trezor wallet includes a screen for an additional level of resistance, however costs $119. </p>

<h2 id="conclusion">Conclusion </h2>

<p>There is no such thing as total security, however the objective of equipment wallets is to make any potential assault more troublesome and asset escalated. Record is no special case – it is intended to render assaults unfeasible by increasing present expectations. </p>

<p>At €29.90, the Ledger Wallet Nano is great incentive for cash, which implies it will engage lovers who need to hold bitcoin yet don't have any desire to spend excessively cash on security, and this is the thing that makes it uncommon in my book. It's not a costly, particular bit of equipment for the chosen few, it's intended for the regular bitcoin client. </p>

<p>The <a href="/buy-bitcoin-with-cash/">gadget can fit on a keychain</a> and the security card in basically any physical wallet, which makes the Ledger extremely reasonable. In the event that you lose either segment, you can in any case recuperate your wallet utilizing your memory helper seed. The up and coming friend versatile application ought to lift security and carry Ledger on a standard with more costly arrangements.</p>
