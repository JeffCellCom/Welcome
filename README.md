

<div id="lockscreen" class="loading">
    <section class="content-header">
	<div style="center;color: #FFFFFF;background:LIGHTSALMON;padding:10px;border:0px solid #000;border-radius:3px">
        <span style="float:right;">
		 <a  href="https://www.xponz.com" target="_blank" style= "color:#FFFFFF;background:darkred;padding:3px;border:1px solid black;border-radius:3px">Official Website</a>&nbsp;
		<a href="#" data-toggle="modal" data-target="#transaction_json_modal" style= "color:#FFFFFF;background:darkred;padding:3px;border:1px solid black;border-radius:3px"><span>Operate Transaction</span></a>		
        </span>
		<h4><b>XPONZ BETA 1.02</b></h4>
		</div>
    </section>
<center>
 <img src="img/brand/logo.png" id="logo-xpz-img" />  
	<div style="margin-bottom:15px;"></div>
	<div style="center;color: #FFFFFF" class="inner"><h5>Xponz blockchain technology provides security for your products, communities, organizations, businesses, digital properties, certificates, social media accounts, identity, voting system, documents, contracts, agreements, financial related transactions or any data that you want to be encrypted and secured inside of its chain. 

It is a Decentralized platform that can utilized by anyone. No policy and authority will control you to used this platform. The Xponz Development Team believes that the real function of decentralized blockchain technology can stand and works by itself  without relying on any centralized exchanges. The decentralized exchange integrated into the blockchain itself to provides convenience for any type of services or transactions that the Xponz technology can offer.

Xponz Cryptocurrency is not a money, its function is to spent base on the type of services or transaction that this blockchain technology can be of service to the users. </h5></div>
</center>
<hr size="10" noshade>


	<div style="center;color: #000000;background:indianred;padding:10px;border:1px solid #000;border-radius:3px">
	<center>
            <div id="login_panel">
                <div class="callout callout-danger custom_login_warning"></div>
                <div class="callout callout-danger" id="testnet_login" data-i18n="testnet_login_warning">Log in with your TestNet account - not your real one!</div>
                <div id="login_error" style="max-width:400px;min-width:400px;display:none">
                    <div class="callout callout-danger"></div>
                </div>
				 <center><div style="center;color: #FFFFFF" ><b> Create Your New Account or Log in to your Xponz Account</b></div></center>
                <div id="account_data_reader" style="display:none;margin:auto;width:384px;height:384px;"></div>
				
				<table style="width:100%;height:100%;">
				<tr><td style="text-align:center;vertical-align:middle">
            <div class="lockscreen-item">
              <div class="lockscreen-credentials">
                <div class="input-group">
                  <input type="password" class="form-control" id="login_password" name="login_password" placeholder="Insert Your Passphrase/Private Key"  autocomplete="" autofocus />
                  <div class="input-group-btn">
                    <button style="center;color: #FFFFFF;background:darkgreen;padding:7px;border:0px solid #000;border-radius:3px" class="btn btn-flat" onclick="NRS.login(1,$('#login_password').val(), null, { isPreventLoginToNewAccount: true })"><b>Log In</b></button>
                  </div>
                  <input type="hidden" name="check_password_length" id="login_check_password_length" value="1" />
                </div>
              </div>
            </div>
			<center>
            <div id="remember_me_container">
              <input type="checkbox" name="remember_me" id="remember_me" /> <label for="remember_me" data-i18n="remember_passphrase_during_session">Remember passphrase on local computer</label>
            </div>
			</center>

                        <input type="hidden" name="check_password_length" id="login_check_password_length" value="0" />
                        <div class="input-group" style="display:none">
                            <input type="password" class="form-control" id="login_password" name="login_password" placeholder="Your Passphrase" data-i18n="[placeholder]your_passphrase" autofocus />
                            <div class="input-group-btn" style="border:1px solid #fff;">
                                <button class="btn btn-flat" onclick="NRS.login(1,$('#login_password').val(), null, { isPreventLoginToNewAccount: true })"><i class="fa fa-arrow-right text-muted"></i></button>
                            </div>
                        </div>
                    </div>
                </div>
				</td></tr>
				</table>
				


				<table style="width:100%;height:100%;">
				<tr><td style="text-align:center;vertical-align:middle">
                <a href="#" class="lockscreen-widget mobile-only btn btn-primary" data-toggle="modal" data-target="#mobile_settings_modal" style="display:none;">
                    <i class="fa fa-navicon"></i>
                </a>
				</tr></td>
				</table>
				<p></p>
				<p></p>
                <div id="registration_link">
                    <button class="btn btn-warning" onclick="NRS.registerAccount();" data-i18n="no_account_q_create_account">Don't have an account? Click here to create one!</button>
                </div>
            </div>

            <div class="panel panel-default" id="welcome_panel" style="display:none;max-width:500px;">
                <div class="panel-body">
                    <button class="btn btn-warning" onclick="NRS.showLoginScreen();return false;" data-i18n="returning_user_q">Returning User?</button>
                    <button class="btn btn-warning" onclick="NRS.registerAccount();return false;" data-i18n="new_q_create_account">Create New Account</button>
                    <a href="#" class="lockscreen-widget mobile-only btn btn-primary" data-toggle="modal" data-target="#mobile_settings_modal" style="display:none;">
                        <i class="fa fa-navicon"></i>
                    </a>
                </div>
            </div>

            <div class="panel panel-default" id="account_phrase_custom_panel" style="display:none;max-width:500px;">
                <div class="panel-body">
                    <form class="form-horizontal" role="form" method="post" autocomplete="off">
                        <div  style="max-width:500px;" data-i18n="passphrase_length_warning">Your passphrase must be at least 35 characters long.</div>

                        <div style="word-break:inherit;">
                            <b data-i18n="attention">Attention</b>:
                            <p data-i18n="passphrase_warning_disclose">
                                Don't ever disclose your passphrase. If you lose it you lose access to your account!
                            </p>
                        </div>

                        <div class="form-group">
                            <label for="registration_password" class="col-sm-3 control-label" data-i18n="passphrase">Passphrase</label>
                            <div class="col-sm-9"><input type="password" name="registration_password" class="form-control" id="registration_password" placeholder="" /></div>
                        </div>
                        <div class="form-group">
                            <label for="registration_password_repeat" class="col-sm-3 control-label" data-i18n="repeat">Repeat</label>
                            <div class="col-sm-9"><input type="password" name="registration_password_repeat" class="form-control" id="registration_password_repeat" placeholder="" /></div>
                        </div>

                        <div style="text-align:right">
                            <input type="submit" class="btn btn-warning btn-sm" value="Register" data-i18n="[value]register" />
                            &nbsp;&nbsp;
                            <button class="btn btn-sm btn-default" onclick="NRS.showLoginOrWelcomeScreen();return false;" data-i18n="cancel">Cancel</button>
                        </div>
                    </form>
                </div>
            </div>

            <div class="panel panel-default" id="account_phrase_generator_panel" style="display:none;max-width:500px">
                <div class="panel-body">
                    <div id="account_phrase_generator_loading">
                        <p><span class="loading_text" data-i18n="loading_word_list">Loading Word List</span><span class="loading_dots"><span>.</span><span>.</span><span>.</span></span></p>

                        <div style="text-align:center;margin-top:20px;margin-bottom:20px;"><img src="img/loading_indicator.gif" alt="Loading..." width="32" height="32" /></div>
                    </div>

                    <div id="account_phrase_generator_loaded">
                        <div class="step_1 account_phrase_generator_steps">
                            <div id="account_phrase_generator_seeder" class="seeder">
                                <p data-i18n="seed_password_generator">Move your cursor around to seed the random number generator...</p>
                                <div class="progress progress-striped">
                                    <div class="progress-bar progress-bar-info" id="account_phrase_generator_seed_progress" role="progressbar" aria-valuemin="0" aria-valuemax="100" style="width: 0;">
                                        <span class="sr-only">0% Seeded</span>
                                    </div>
                                </div>
                            </div>

                            <div style="text-align:right">
                                <button class="btn btn-sm btn-default" onclick="NRS.showLoginOrWelcomeScreen();return false;" data-i18n="cancel">Cancel</button>
                            </div>
                        </div>

                        <div class="step_2 account_phrase_generator_steps">
                            <div id="account_phrase_generator_start">
                                <p><span data-i18n="generating_passphrase_wait">Generating your passphrase. Please wait</span><span class="loading_dots"><span>.</span><span>.</span><span>.</span></span></p>

                                <div style="text-align:center;margin-top:20px;margin-bottom:20px;"><img src="img/loading_indicator.gif" alt="Loading..." width="32" height="32" /></div>
                            </div>

                            <div id="account_phrase_generator_stop" style="display:none">
                                <p data-i18n="automatically_generated_passphrase_is">Your automatically generated passphrase is:</p>
                                <textarea style="width:100%;height:50px;margin-bottom:10px;padding:3px;" rows="2" readonly></textarea>
                                <p data-i18n="memorize_passphrase_help">Please write down or memorize these 12 words (their order and capitalization matters - always lowercase). This passphrase is needed in order to access your Xpz account.</p>
                                <p data-i18n="your_account_is">Your public account address is: </p>
                                <input id="step_2_account" style="width:100%;height:50px;margin-bottom:10px;padding:3px;" readonly></input>
                                <div class="paper-wallet-link-container" style="display: none;">
                                    <button class="btn btn-warning" href="#" id="generator_paper_wallet_link" data-i18n="print_paper_wallet">Print Paper Wallet</button>
                                </div>
                                <p></p>
                                <div>
                                    <strong><span data-i18n="attention">Attention</span></strong>:
                                    <span data-i18n="passphrase_warning_disclose">
                                        Don't ever disclose your passphrase. If you lose it you lose access to your account!
                                    </span>
                                </div>
								<p></p>
                                <div id="confirm_passphrase_warning_container">
                                    <input type="checkbox" id="confirm_passphrase_warning" value="0"/> <span></span>
                                    <label for="confirm_passphrase_warning" data-i18n="confirm_passphrase_warning">I will not forget my passphrase and I will never disclose it</label>
                                </div>
                                <div style="text-align:right">
                                    <input type="submit" class="btn btn-warning btn-sm" value="Next" data-i18n="[value]next" onclick="NRS.createPassphraseToConfirmPassphrase()" />&nbsp;&nbsp;
                                    <button class="btn btn-sm btn-default" onclick="NRS.showLoginOrWelcomeScreen();return false;" data-i18n="cancel">Cancel</button>
                                </div>
                            </div>
                        </div>

                        <div class="step_3 account_phrase_generator_steps">
                            <p data-i18n="passphrase_write_below">Your passphrase is very important! In order to be sure that you have saved it, please write your passphrase below:</p>

                            <div class="callout callout-danger" style="display:none" data-i18n="incorrectly_typed_passphrase">You have not typed the passphrase correctly, please try again!</div>

                            <textarea style="width:100%;height:50px;margin-bottom:10px;" rows="2"></textarea>

                            <div style="text-align:right">
                                <input type="submit" class="btn btn-warning btn-sm" value="Next" data-i18n="[value]next" onclick="NRS.verifyGeneratedPassphrase();return false;" />
                                &nbsp;&nbsp;
                                <button class="btn btn-sm btn-default" onclick="NRS.showLoginOrWelcomeScreen();return false;" data-i18n="cancel">Cancel</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="custom_passphrase_link">
                <button class="btn btn-warning" onclick="NRS.registerUserDefinedAccount();" data-i18n="choose_own_passphrase">Want to choose your own passphrase? Click here.</button>
            </div>
			</center>
		</div> 


	<br>


				 <div class="dashboard_first_row row">
            <div class="col-lg-6 col-xs-6">
					<div style="center;color: #FFFFFF;background:indianred;padding:10px;border:1px solid #000;border-radius:15px">
						<center><h5> <b>USE CASES</b></center>
                        <hr size="10" noshade>
						<b>Private Contract Data Base:</b>&nbsp;Xponz Blockchain can be use by communities, businesses, organizations or any individuals that are looking for
						cheap cost with superb security service private contract/agreement inside the Xponz Blockchain data base system. Anyone can create a network inside of blockchain
						with multi function security features for their communities without any central authority unlike the centralized social media that anytime they can be 
						disabled, control, view their private activities.<br>	
						<br>
						<u><b>Communities, Organization, Businesses Use Cases:</b></u>&nbsp; 
						<li>Private Organizations Banking System(proof of Funds).</li> 
						<li>Recording and issuing certificates that can be verified the authenticity easily.</li>
						<li>Accurate Sales Distribution/Inventory that required approval by the business owners.</li>
						<li>Product Registration, recording a product inside the Xponz Blockchain before its distribution will protect and help your business, at the same time it will protect your consumer to easily identify and verify the authenticy of the product(Anti-Piracy).</li>
						<li>Reward Points Issuance(for business owners).</li> 
						<li>ID System, Voter's ID or Community membership authenticity that can help to verify the legitimate members easily.</li> 
						<li>Digital Ownership Certificate that provides security to the owner of expensive
						goods or property and to prevent to be sold when it get stolen.(ex. Mobile phone, Jewelries, Expensive goods).</li>
						<li>EMAIL System, No central authority can peek your data or important information when you use Xponz as Email function.</li>
						<li>Xponz can protect your Physical/Digital Creation Properties, it will serve as a mark of ownership or authorship of your creations such as albums, ebook creation, books, songs, movies, formula, codes, script, etcetera.</li>
						Xponz Blockchain Technology could provide more services in terms of security features. There are 101 ways to use Xponz Blockchain Technology.
						</h5>
						<div style="margin-bottom:1px;"></div>
					
		</div>
				 <div style="margin-bottom:15px;"></div>
	</div>



						<div style="margin-bottom:1px;"></div>
			<div class="optional_dashboard_tile col-lg-6 col-xs-6">			
				    <div style="center;color: #FFFFFF;background:indianred;padding:10px;border:1px solid #000;border-radius:15px">
					<center><h5> <b>XPONZ BLOCKCHAIN 2.0 SPECIFICATION</b><br></center>
                        <hr size="10" noshade>
                        
						<center>XPONZ – Cryptocurrency with Proof-of-Stake (PoS) forging/mining</center>						
						<br>
						<li><b>Ticker:</b> XPZ</li>
						<li><b>Total Coins:</b> 1,350,000,000 Xponz</li>
						<li><b>Decimal:</b> 8</li>
						<li><b>1 XPZ:</b> 100,000,000 ZEN</li>
						<li><b>Algorithm:</b> SHA-256</li>
						<li><b>Encryption Algorithm:</b> Curve25519</li>
						<li><b>Block generation:</b> 10-60 sec. Maximum 0.2 seconds</li>
						<li><b>Transactions per Block:</b> 256 transactions</li>
						<li><b>Max. Attachment Size:</b> 42 kb</li>
						<li><b>PoS Difficulty:</b> Recalculated every two blocks (Real time Difficulty Adjustment)</li>
						<li><b>PoS Reward:</b> Transaction fees only</li>
						<li><b>Minimum Transaction Fee:</b> 0.005 XPONZ</li>
						<li><b>Required Balance to Mine/Forge:</b> 10,000 XPONZ</li>
						
						<br>
						Start Mining by forging your balance and not CPU or GPU power.
						Less power consumption, more efficient, and less network maintenance.</h5>
						<br>
						<hr size="10" noshade>	
						<center><b>Xponz Blockchain Decentralized Features</b></center>
						<hr size="10" noshade>
						<li>Decentralized Data base access network with multiple security function</li>
						<li>Communities Private Network ID System</li>
						<li>Voting System with Voter's ID</li>
						<li>Peer to Peer Contract/Agreement Transactions that could set/require multiple parties to approve thru digital block signatures (100% Privacy)</li>
						<li>Decentralized Two-Factor Authorization (2FA)</li>
						<li>Email/Messaging System(100% Privacy)</li>
						<li>Certificate Issuance (Transferable, Non-Transferable)</li>
						<li>Organization's Private Banking System</li>
						<li>Digital Certificate Proof of Ownership</li>
						<li>Digital Property's Proof of Authorship</li>
						<li>Product's Proof of Authenticity</li>
						<li>Merchant's Reward Point system, Incoming/Outgoing Sales Inventory</li>
						<li>Smart Transactions</li>
						<li>Costumized Proof of Authority transactions</li>
						<li>"Security" Payment Solution</li>
						<li>Decentralized Exchange</li>
						<li>And many more....</li>
						
							
		</div>
				<div style="margin-bottom:15px;"></div>
		</div>
	   </div>
        </div>
 
</div>
