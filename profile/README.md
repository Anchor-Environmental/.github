<head>
  <a href="https://anchorenvironmental.co.za/">
    <img width="25%" src="./Anchorlogo.svg" alt="Anchor Logo">
  </a>
  <link
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
  rel="stylesheet"
/>
</head>

<body>
  <p>
  <h1>
    <b>
    Welcome to the Anchor Environmental GitHub! ⚓
    </b>
  </h1>
</p> 
</body>

---
### About us ❔:
    Anchor Environmental is a group of companies offering ecological, social 
    and economic assessment, research, monitoring and natural capital 
    accounting to inform environmental management and policy. Our work 
    straddles marine, estuarine, freshwater and terrestrial realms; and it 
    addresses decision-making, planning, policy and strategy regarding 
    sustainable development and the conservation and management of 
    biodiversity, resources and ecosystem services in the context of a range
    of pressures including climate change. We are based in South Africa and
    Namibia, with our head office in Cape Town.

### Description ✍️:
    This is the home for code that we write for projects. The code does
    not have to be oraganised according to a project. You can create a
    repo and store it for each use case. We can pull all the code together
    based on whats required for a project and it can be updated accordigly!

### Usage/Guide 🦮:
    1. Follow the links to the repective repo
    2. Click on the <> Code button and copy the https url
    3. Open a terminal/shell at your local directory and paste the following
       command with your link:

```Shell
git clone "paste link here"
```

### Code Structure 🗺️:
```mermaid
%%{init: {'theme':'base', 'themeVariables': {
      'primaryColor': '#61778d',
      'primaryTextColor': '#fff',
      'primaryBorderColor': '#8495a6',
      'lineColor': '#2c2c2c',
      'secondaryColor': '#8495a6',
      'tertiaryColor': '#8495a6'
    }}}%%
flowchart LR
  A(repos 📃):::layer0-->B(Project specific):::layer1
  B-->C(2073_file_processing):::layer2
  B-->J(2073_mercator_processing):::layer2
  B-->E(2073_delft_file_conversions):::layer2
  B-->M(2026_Windfarms):::layer2
  B-->O(SkiMonkey):::layer2
  B-->D(2073_projection_mapping):::layer2
  A(repos 📃)-->F(general):::layer1
  F-->G(visualisations):::layer2
  F-->D(2073_projection_mapping):::layer2
  F-->I(GUI_Base):::layer2
  F-->K(species_database_generator):::layer2
  F-->L(CTD_processing):::layer2
  F-->N(testR):::layer2
  F-->P(Docking):::layer2

 classDef layer0 fill:#2b3846
 classDef layer1 fill:#61778d
 classDef layer2 fill:#8495a6
```

### Useful git commands 👨🏾‍💻:

```Shell
git --help                                          # list all commands
git clone "paste link here"                         # copy git repository from github to local machine
git init                                            # initialise empty git repository in current working directory
git add "path to file"                              # stage tracked changes use . as the path for all files
git log                                             # show all commits
git branch "name"                                   # create new branch of current branch
git commit -m "commit message"                      # commit all staged changes
git push --set-upstream "repo url" "branch name"    # push current branch to remote branch at soecified url
git checkout "item"                                 # check out specified commit or branch
```
  ---


