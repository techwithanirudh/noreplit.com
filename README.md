<h1 id="heading">noreplit.com</h1>
  <i>Disclaimer: This is about community management and pricing. The tech, design & prototyping are all great.</i>
  <a href="https://twitter.com/coding398/status/1710604447641133478">retweet</a><br/>
  <i>Disclaimer 2: This looks much better on <a href="https://noreplit.com">the site</a></i>
  <hr>
  <p id="desc"> Over the past few months, Replit.com has changed their pricing drastically to the point where it is
    simply not
    viable.
    <br> We, along with many others, have used Replit for years, however, at its current point we are all looking for
    alternatives.
    <br> This website covers <b>what happened, a comparison, alternatives, and community quotes</b> to give perspective
    on the current issues of the platform.
  </p>
  <hr>
  <h3>What happened?</h3>
  <section id="whatHappened">
    <div class="card">
      <h3>Nerfing Hacker Plan</h3>
      <p>
        The cutback of "Always On" instances from five to one hit Hacker Plan users hard. This shift took many projects
        offline, with users unable to pay the extra $292.20/year for 4 more always on repls.
      </p>
      <p>
        Similarly, reducing the number of Boosts included in the Hacker Plan from five to one, and reducing base repl
        specs to the same level as the free plan, unless you were actively inside the Replit workspace, left users
        wondering how Replit Hacker plan could anymore be a justified expense.
      </p>
    </div>
    <div class="card">
      <h3>Outrageous AI</h3>
      <p>
        Replit's enduring focus on AI and LLMs have put them in a state of throwing money at a losing battle.
        Ghostwriter is $10/month, yet it uses the same technology one can get for extraordinarily less from OpenAI.
      </p>
      <p>
        Trending Repls have been heavily focused on AI, as well as the company's social media accounts & most heavily,
        their CEO.
      </p>
      <p>
        However, it must be said, integrating AI has always been one of the main goals of Replit, right from day 1. It
        just feels overemphasised currently. AI is undoubtedly a very interesting space in computer science right now,
        however it's not the only one. A balance should be made such that AI exists within the product and community,
        but is not such an overwhelming majority of the focus as it is now.
      </p>
    </div>
    <div class="card">
      <h3>10x Hike in Power-ups</h3>
      <p>
        Replit's price hike for power-ups like Boosts and the Always On feature greatly affected its large student and
        budding coder user base. The increased costs, from 2 to 70 cycles/day, for a Boost, and 2 to 20 cycles/day, for
        the Always On feature, made these features less accessible, impacting the budget community.
      </p>
      <p>
        Replit has previously been very focused on their platform being used for new coders, with their motto
        "Bringing the next billion software creators online". However, this target audience has changed recently, with
        low budget beginner, student, and hobby developers being pushed away by the increased pricing.
      </p>
    </div>
    <div class="card">
      <h3>Reserved VM Pricing</h3>
      <p>
        The first offender of their Deployments is Reserved VMs. For the lowest tier, <b>you get 0.25vCPUs, 1GiB of RAM,
          and 10GiB of outbound data transfer.</b></p>
      <p>On platforms such as DigitalOcean and AWS, they can be more than 70%
        cheaper.</p>
      <table class="comparison">
        <thead><tr>
          <th class="vendor">Replit.com - $6.40/month</th>
          <th class="vendor">DigitalOcean.com - $6.00/month</th>
        </tr></thead>
        <thead><tr>
          <th class="value">0.25vCPU/1GB RAM/10GB transfer</th>
          <th class="value">1vCPU/1GB RAM/1TB transfer</th>
        </tr></thead>
      </table>
    </div>
    <div class="card">
      <h3>Potentially Misleading "Autoscale"</h3>
      <p>Replit's version of a worker-like VM is Autoscale. You get <b>3 MILLION</b> free compute "units" per month with
        Hacker.</p>
      <p>
        If you're confused by what that means, everyone else is too. Replit's site says that most projects will use
        under 20 cents a month, however with a DDoS bypass or a "viral repl", you can easily incur costs upwards of
        hundreds of dollars. You can help mitigate this, by setting a limit on your monthly spending, but the lowest,
        as of writing this, is $10.</p>
      <p>
        On their pricing page, if you had the <b>Lowest Tier</b> Autoscale running for a full month with constant load,
        you would incur ~$64/month.</p>
    </div>
    <div class="card">
      <h3>Uncompetitive Static</h3>
      <p>Replit's static deployments is just that - static site hosting. Just one small issue, and pay attention - all
        of these sites below are free.</p>
      <table class="comparison">
        <thead><tr>
          <th class="vendor">Replit.com</th>
          <th class="vendor">Github Pages</th>
          <th class="vendor">Cloudflare Pages</th>
        </tr></thead>
        <thead><tr>
          <th class="value">10GiB transfer</th>
          <th class="value">100GiB transfer</th>
          <th class="value">Unlimited* transfer</th>
        </tr></thead>
      </table>
      <i>*Cloudflare's Pages obviously isn't unlimited, however will incur terabytes of transfer before you may get a
        friendly email.</i>
    </div>
    <div class="card">
      <h3>Egress Limits</h3>
      <p>
        On April 7, 2023, Replit set egress limits across all plans. Aimed at controlling outbound data transfer, this
        move faced backlash, especially from the Free tier users.
      </p>
      <p>
        With limits set at 10 GiB for Free, 50 GiB for Hacker, and 100 GiB for Pro tiers, many found them restrictive.
        Particularly those on the free plan, hosting popular projects.
      </p>
      <table class="comparison">
        <thead><tr>
          <th class="vendor">Replit.com</th>
          <th class="vendor">DigitalOcean.com</th>
        </tr></thead>
        <thead><tr>
          <th class="value">$0.1/GiB, 10GiB FREE</th>
          <th class="value">$0.01/GiB, 500GiB FREE</th>
        </tr></thead>
      </table>
    </div>
    <div class="card">
      <h3>Replit.dev</h3>
      <p>
        The final blow came when Replit announced that your repls could only stay online when you are actively within
        the workspace, now Replit Deployments stand as Replit's only hosting option.
      </p>
      <p>
        This decision seemed to counter Replit's user-friendly ethos, sparking widespread confusion and shock within the
        community. Especially as they promised to <a href="https://blog.replit.com/glitch#~text=But%20we%20will%20never%20ban%20pinging%20to%20force%20people%20to%20upgrade%20by%20taking%20away%20features.:~:text=But%20we%20will%20never%20ban%20pinging%20to%20force%20people%20to%20upgrade%20by%20taking%20away%20features.">
        never force users to move away from pingers to a paid product</a>, which is exactly was just been done. Users
        can no longer ping their hosted repl's repl.co url, and instead must move to the paid deployments product to
        continue hosting on Replit.
      </p>
    </div>
    <div class="card">
      <h3>Misleading Bounties</h3>
      <p>
        The top 50 most "rewarding" open bounties are all stale, having been left open for months with no accepted
        applicant. Replit still shows this on their "$60k+ OPEN" tag, even though there is no hope of acquiring this
        money from those stale bounties.
      </p>
      <p>Another issue is that the payout is shown in USD and Cycles, but doesn't take into account the 25%-15% cashout
        fee, giving a slightly misleading expectation to new bounty hunters who aren't yet aware of the fee.</p>
    </div>
    <div class="card">
      <h3>Terrible community management</h3>
      <p>
        The 16k+ member Replit Discord community fell to bits after the moderation team wasn't paid any more than their
        Hacker plan, all nerfed and shiny at $7/month. Understandably, moderators striked, causing Replit to abandon
        control of the community server altogether.
      </p>
      <p>
        The Replit Reps program was abandoned too, with it disbanding after only 1 and a half cohort cycles.
      <p>
        Jams were reduced from events like <b>Kajam</b> and <b>#madewithreplit</b> to AI hackathons that a 14 year old
        won with school & no prior experience. Prize pools have dropped from over $10k to around $2k per event, lowering
        the incentive.
      </p>
    </div>
  </section>

  <br>
  <hr>

  <section id="comparison-table">
    <h3>The Ultimate Comparison Table™</h3>
    <table>
      <thead>
        <tr>
          <th></th>
          <th>Replit</th>
          <th>DigitalOcean</th>
          <th>AWS</th>
        <tr>
      </thead>
      <tbody>
        <tr>
          <th>Transfer ($6/month VM)</th>
          <td>10 GiB free, $0.1/GiB</td>
          <td>1,000 GiB free, $0.01/GiB</td>
          <td>$0.08 - $0.2/GiB</td>
        </tr>
        <tr>
          <th>Storage ($6/month VM)</th>
          <td>10 GB</td>
          <td>25 GB</td>
          <td>Depends, varies wildly</td>
        </tr>
        <tr>
          <th>vCPUs ($6/month VM)</th>
          <td>0.25</td>
          <td>1</td>
          <td>Around 2</td>
        </tr>
        <tr>
          <th>RAM ($6/month VM)</th>
          <td>1GB</td>
          <td>1GB</td>
          <td>1GB</td>
        </tr>
        <tr>
          <th>Database (per GB)</th>
          <td>10 GB for $1/day</td>
          <td>$0.5-$1/GB (higher, cheaper)</td>
          <td>$0.115/GB</td>
        </tr>
        <tr>
          <th>Accessibility</th>
          <td>Very easy</td>
          <td>Intermediate, tutorials</td>
          <td>Expert, easy to lose money</td>
        </tr>
      </tbody>
    </table>
    <br>
    <h3>Static</h3>
    <table>
      <thead>
        <tr>
          <th></th>
          <th>Replit</th>
          <th>Github</th>
          <th>CF Pages</th>
        <tr>
      </thead>
      <tbody>
        <tr>
          <th>Storage</th>
          <td>Account-based, $0.15/GB extra</td>
          <td>1GB</td>
          <td>500GB (absolute max)</td>
        </tr>
        <tr>
          <th>Transfer</th>
          <td>Account-based, $0.1/GiB extra</td>
          <td>100GiB</td>
          <td>Unlimited</td>
        </tr>
      </tbody>
    </table>
  </section>

  <hr>

  <h3>Alternatives</h3>
  <h4>Completely Free</h4>
  <ol>
    <li>
      <p><a href="https://glitch.com/">Glitch</a></p>
      <ul>
        <li>Glitch is an online coding platform that emphasizes creative and collaborative
          coding. It allows you to create and remix projects, experiment with coding, and collaborate with others in
          real time. It is, however, only suitable for building web applications.</li>
      </ul>
    </li>
    <li>
      <p><a href="http://goorm.io/">Goorm</a>, Credit: python660</p>
      <ul>
        <li>Goorm is a cloud-based development platform originating in South Korea that
          offers a robust set of features. It provides flexibility in choosing programming languages, database options,
          and Ubuntu OS versions. With a generous amount of storage and a daily traffic limit of 1GB, it is suitable for
          both small and medium-sized projects. The platform also supports both public and private projects.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://codesandbox.io/">CodeSandbox</a></p>
      <ul>
        <li>CodeSandbox is an online development environment tailored for web
          applications. It offers a convenient way to create, edit, and test React, Vue, and Angular projects in a
          sandboxed environment, making it easy to prototype and share code.</li>
      </ul>
    </li>
    <li>
      <p><a href="http://stackblitz.com/">StackBlitz</a></p>
      <ul>
        <li>StackBlitz offers an online IDE for web development with features like
          real-time collaboration and instant dependency searches. It's tailored for front-end development and supports
          popular web frameworks like Angular, React, and Vue.js.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://hop.io/">Hop</a></p>
      <ul>
        <li>Hop provides an online coding platform that allows you to write, compile, and
          run code in various programming languages. It offers a user-friendly interface for programming using VSCode.
        </li>
      </ul>
    </li>
    <li>
      <p><a href="https://github.com/features/codespaces">GitHub Codespaces</a></p>
      <ul>
        <li>GitHub Codespaces integrates with GitHub repositories, enabling you to create
          and customize development environments for your projects directly in your browser. This is particularly useful
          for collaborative coding and maintaining consistent development environments across team members.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://gitpod.io">Gitpod</a></p>
      <ul>
        <li>Gitpod offers ready-to-code development environments for GitHub projects,
          allowing you to start coding immediately without any setup.</li>
      </ul>
    </li>
    <li>
      <p><a href="http://cyclic.sh/">Cyclic.sh</a>, Credit: python660</p>
      <ul>
        <li>Cyclic.sh is a specialized platform for hosting and running scheduled jobs or
          periodic tasks. The service focuses on ease of use and scalability, allowing you to set up, run, and monitor
          recurring tasks without the hassle of managing servers or cron jobs.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://vercel.com/">Vercel</a></p>
      <ul>
        <li>Vercel is a cloud platform that specializes in deploying and hosting web
          applications. It's known for its speed and ease of use, supporting various frameworks and offering features
          like serverless functions and automatic scaling.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://www.netlify.com/">Netlify</a></p>
      <ul>
        <li>Netlify is a platform focused on web development and deployment. It offers
          features like continuous integration, automated deployments, and hosting for static sites and web
          applications. It simplifies the process of deploying and managing web projects.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://pages.cloudflare.com/">Cloudflare Pages</a></p>
      <ul>
        <li>Cloudflare Pages is a free way to deploy static sites. It's great for
          production-level deployment, providing you with a [project].pages.dev URL, along with support for custom
          domains and more.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://static.app">Static</a></p>
      <ul>
        <li>Static is a platform that offers simple and fast deployment of static websites
          with a focus on performance and security.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://onrender.com">Render</a></p>
      <ul>
        <li>Render is a unified platform to build and run all your apps and websites with
          free SSL, a global CDN, private networks, and auto deploys from Git.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://coder.com">Coder</a></p>
      <ul>
        <li>Coder provides an enterprise-grade development environment that allows
          developers to code from anywhere.</li>
      </ul>
    </li>
  </ol>
  <h4>Credit Card Required</h4>
  <ol>
    <li>
      <p><a href="https://www.heroku.com/">Heroku</a></p>
      <ul>
        <li>Heroku is a cloud platform that enables you to deploy, manage, and scale
          applications. It supports various programming languages and provides tools for continuous integration and
          delivery.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://www.digitalocean.com/">Digital Ocean</a></p>
      <ul>
        <li>Digital Ocean provides cloud services that help businesses deploy, manage, and
          scale applications. Their droplets are versatile Linux-based virtual machines.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://aws.amazon.com/ec2/">AWS EC2</a></p>
      <ul>
        <li>Amazon EC2 (Elastic Compute Cloud) is a web service that provides resizable
          compute capacity in the cloud, allowing you to run applications on Amazon's computing environment.</li>
      </ul>
    </li>
    <li>
      <p><a href="https://www.oracle.com/cloud/">Oracle Cloud</a></p>
      <ul>
        <li>Oracle Cloud offers a comprehensive suite of cloud services, including
          computing power, storage options, and networking capabilities.</li>
      </ul>
    </li>
  </ol>
  <p>These alternatives offer a range of features for coding, collaboration, deployment, and experimentation, catering
    to various development needs and preferences.</p>
  <footer>
    <p>
      List by <a href="https://replit.com/@techwithanirudh">@techwithanirudh</a>
    </p>
  </footer>

  <hr>

  <h3>Community quotes</h3>

  <quote>
    "I've already moved a ton of stuff to DigitalOcean. I won't be coming back. I've had chats with team members, and
    it's clear that nothing's changing. I'll stay in the community, maybe use it for prototyping, but that's about it."
    <span>~ coding398</span>
  </quote><br/><br/>
  <quote>
    "Whilst Replit may be the most convenient option, you're paying too much for tha convenience and they don't provide
    you with enough customisability of what you pay for."
    <span>~ DillonB07</span>
  </quote><br/><br/>
  <quote>
    "The young aspiring developers that made Replit the company it is today ultimately have been abandoned and kicked to
    the curb by the platform with rising costs and and restrictions."
    <span>~ zavexeon</span>
  </quote><br/><br/>
  <quote>
    "I hope Replit reconsiders the replit.dev thing. Otherwise, it could negatively impact many users. 😔"
    <span>~ techwithanirudh</span>
  </quote><br/><br/>
  <quote>
    "You will need either money or a ton of cycles to host a site on Replit. Either one could be acquired by your mom’s
    credit card, however you could also get cycles by completing bounties or getting tipped on your Repls."
    <span>~ CoderElijah</span>
  </quote><br/><br/>
  <quote>
    "So, what? Replit is just not free anymore? Hosting on Replit was already frustrating enough with the slow speeds
    and the sleepy repls, and now you’re just pulling the plug entirely? Wow."
    <span>~ wutadamyt</span>
  </quote><br/><br/>
  <quote>
    "I used to use Replit a lot. But now, I can't find myself using it in the near future. I don't like what Replit has
    done to the platform, and I am in the process of switching over to better, cheaper cloud providers."
    <span>~ datkat21</span>
  </quote>
  <quote>
    "I was a power-user a little while back. Migration would be hell. I have tons of websites to port over, and it won't be fun. And that's what <i>was</i> amazing about Replit, you could basically make anything you wanted at any time, at any rate. It's what kept my motivation super high, Now that motivation has dried up."
    <span>~ EnZon3</span>
  </quote>

  <hr>
  <h3>Wrapping up</h3>

  <p>Want to contribute to this site? <a href="https://github.com/codingMASTER398/noreplit.com">Submit a PR</a>!<br>
    This is in no way an attack on any Replit employees - moreso the pricing & direction.<br>
    Want something removed that's yours? Reach out to coding398@outlook.com<br>
    Thanks to @techwithanirudh, DillonB07, Firepup6500, datkat21 and py660 for helping with the website.<br>
    <b>This site was deployed with CloudFlare Pages.</b>
    <br>
    <br>
    Created by <a href="https://coding398.dev">coding398</a>.
  </p>
