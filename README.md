# Sample Usage

local WindShake = require(path)

WindShake:Init({
    MatchWorkspaceWind = true, -- WindShake will use workspace.GlobalWind
})

-- Anything with the 'WindShake' tag will now shake