-- D’Menor Group · Rota e Armação v1.15
-- Arquivo independente. Controlador de rota derivado da v5.45.
-- Rota de coleta obtida da exportação do usuário.
local DATA = game:GetService("HttpService"):JSONDecode([==[{"placeId":9417205094,"placeVersion":20054,"points":[{"routeId":"1","prompt":"Workspace.Construcoes.LocaisRotas.Local1.npc3.ProximityPrompt","seatCFrame":[4101.17236328125,63.780662536621094,480.6103820800781,-0.9937888979911804,-0.000922285602428019,-0.11127795279026031,0.00031906343065202236,0.9999379515647888,-0.011137067340314388,0.11128132045269012,-0.01110339816659689,-0.993726909160614]},{"routeId":"2","prompt":"Workspace.Construcoes.LocaisRotas.Local2.npc2.ProximityPrompt","seatCFrame":[4321.37158203125,52.37744140625,3277.02783203125,0.0718580037355423,0.009477567858994007,0.9973698258399963,0.00034015788696706295,0.9999545812606812,-0.009526636451482773,-0.9974148273468018,0.0010238282848149538,0.07185151427984238]},{"routeId":"3","prompt":"Workspace.Construcoes.LocaisRotas.Local3.npc4.ProximityPrompt","seatCFrame":[1787.2138671875,2.355504274368286,2162.236328125,0.9993020296096802,0.0006973249837756157,0.03734974563121796,-0.00030523966415785253,0.999944806098938,-0.010502343997359276,-0.037355005741119385,0.01048361323773861,0.9992470741271973]},{"routeId":"4","prompt":"Workspace.Construcoes.LocaisRotas.Local4.npc5.ProximityPrompt","seatCFrame":[356.662353515625,28.83515167236328,-838.380615234375,0.8041670322418213,0.1763123720884323,-0.5676525235176086,-0.23425370454788208,0.9717111587524414,-0.030043719336390495,0.5462971925735474,0.15713486075401306,0.8227198719978333]},{"routeId":"5","prompt":"Workspace.Construcoes.LocaisRotas.Local5.npc3.ProximityPrompt","seatCFrame":[575.6602172851562,2.6870570182800293,3192.822021484375,-0.11640595644712448,0.014811435714364052,0.9930912852287292,0.000361314247129485,0.9998893737792969,-0.014870474115014076,-0.9932016730308533,-0.0013721938012167811,-0.11639843136072159]},{"routeId":"6","prompt":"Workspace.Construcoes.LocaisRotas.Local6.npc5.ProximityPrompt","seatCFrame":[2764.1865234375,2.641146659851074,2734.322021484375,-0.9999544024467468,0.00005250068352324888,-0.009551770985126495,0.0001316069538006559,0.9999657273292542,-0.008281402289867401,0.00955100916326046,-0.008282281458377838,-0.9999200701713562]},{"routeId":"7","prompt":"Workspace.Construcoes.LocaisRotas.Local7.npc3.ProximityPrompt","seatCFrame":[3189.755615234375,2.7162067890167236,2254.88671875,-0.9996694326400757,-0.0009585406514815986,0.02569250389933586,-0.0016507747350260615,0.9996358156204224,-0.026935383677482605,-0.025657329708337784,-0.02696889266371727,-0.9993069767951965]},{"routeId":"8","prompt":"Workspace.Construcoes.LocaisRotas.Local8.npc5.ProximityPrompt","seatCFrame":[5298.68603515625,78.57240295410156,-1547.37744140625,0.3910984396934509,-0.009962188079953194,-0.9202949404716492,0.0002688069362193346,0.9999426007270813,-0.010710138827562332,0.9203488230705261,0.0039413366466760635,0.3910786509513855]},{"routeId":"9","prompt":"Workspace.Construcoes.LocaisRotas.Local9.npc2.ProximityPrompt","seatCFrame":[2868.832275390625,2.4963159561157227,3179.705078125,0.0626436099410057,-0.03931587561964989,-0.9972612857818604,-0.00005711756966775283,0.9992236495018005,-0.03939682990312576,0.9980359673500061,0.002524920739233494,0.06259272992610931]},{"routeId":"10","prompt":"Workspace.Construcoes.LocaisRotas.Local10.npc4.ProximityPrompt","seatCFrame":[3214.860595703125,63.58363342285156,665.2692260742188,-0.9998823404312134,-0.003636130830273032,0.014904269017279148,-0.0037685169372707605,0.9999536275863647,-0.008863985538482666,-0.014871346764266491,-0.008919109590351582,-0.9998496174812317]},{"routeId":"11","prompt":"Workspace.Construcoes.LocaisRotas.Local11.npc4.ProximityPrompt","seatCFrame":[800.6470336914062,57.84016036987305,2403.8388671875,0.9973958134651184,0.0005083237774670124,0.07212024927139282,0.0002942999708466232,0.9999381303787231,-0.011117902584373951,-0.07212144136428833,0.011110174469649792,0.9973340034484863]},{"routeId":"12","prompt":"Workspace.Construcoes.LocaisRotas.Local12.npc2.ProximityPrompt","seatCFrame":[433.0311584472656,17.877315521240234,890.1922607421875,0.9984599351882935,0.04460599273443222,0.032985977828502655,-0.047152552753686905,0.9956024885177612,0.08094648271799088,-0.029230225831270218,-0.08237719535827637,0.9961724877357483]},{"routeId":"13","prompt":"Workspace.Construcoes.LocaisRotas.Local13.npc3.ProximityPrompt","seatCFrame":[827.03125,2.4932444095611572,2414.046630859375,0.04927742853760719,0.04190920665860176,0.9979054927825928,0.0003084705676883459,0.9991186261177063,-0.04197538644075394,-0.9987850785255432,0.0023762634955346584,0.04922106862068176]},{"routeId":"14","prompt":"Workspace.Construcoes.LocaisRotas.Local14.npc3.ProximityPrompt","seatCFrame":[2338.02392578125,2.9372122287750244,3770.05322265625,-0.020307615399360657,-0.011188429780304432,-0.999731183052063,0.00027690030401572585,0.9999372959136963,-0.011196360923349857,0.9997937679290771,-0.000504197261761874,-0.02030324377119541]},{"routeId":"15","prompt":"Workspace.Construcoes.LocaisRotas.Local15.npc5.ProximityPrompt","seatCFrame":[4037.1650390625,11.959478378295898,-1724.8482666015625,0.9996153712272644,0.0003302202676422894,0.027730155736207962,-0.0000475595734314993,0.9999480247497559,-0.010193301364779472,-0.027732081711292267,0.010188061743974686,0.999563455581665]}]}]==])

local WAREHOUSE=game:GetService("HttpService"):JSONDecode([==[{"placeVersion":19904,"serverJobId":"b39cba79-c6e4-4044-820a-619c2ebce027","parking":{"seatCFrame":[3839.3251953125,2.826720714569092,2097.12353515625,-0.8869271278381348,0.005347418133169413,0.46187835931777954,0.0003250177251175046,0.9999399781227112,-0.010952731594443321,-0.4619092047214508,-0.009564156644046307,-0.8868756294250488],"vehicleModel":"Toyota","seatPath":"Workspace.CarrosSpawnados.Toyota.DriveSeat"},"userId":4416614182,"start":{"seated":false,"actionText":"Iniciar Rota","objectText":"","rootCFrame":[3866.23291015625,22.603513717651367,2103.684814453125,0.21608032286167145,6.653640127751714e-8,-0.9763755798339844,3.155865968551552e-8,1,7.513052224794592e-8,0.9763755798339844,-4.704733314042642e-8,0.21608032286167145],"promptPath":"Workspace.SystemFacsRua.FacsOcupadas.mafia YAKUZA .MelhoriasProxys.Rotas.Proxit.ProximityPrompt","key":"E","promptPosition":[3868.67822265625,23.39545249938965,2103.1220703125],"triggerConfirmed":true,"maxActivationDistance":8,"holdDuration":0},"placeId":9417205094,"schema":1,"noDelivery":true}]==])
local Players = game:GetService("Players")
local HttpService = game:GetService("HttpService")
local player = Players.LocalPlayer
assert(player, "Execute no cliente.")
assert(game.PlaceId == DATA.placeId, "Este script usa a rota do PlaceId " .. DATA.placeId)
local playerGui = player:WaitForChild("PlayerGui")
assert(not playerGui:FindFirstChild("DMenorGroupAutoRota"), "A auto coleta já está aberta.")
local UserInputService = game:GetService("UserInputService")
local TweenService = game:GetService("TweenService")
local running, busy, repeatRoute = false, false, false
local retryGeneration, retryCount = 0, 0
local rescueAttempts=0
local rescueBlocked=false
local lastConfirmedPoint
local function cancelAutoRetry(resetCount)
    retryGeneration=retryGeneration+1
    if resetCount then retryCount=0 end
end
local fabrication={active=false,bench=nil,sent=0}
local cfg = {antiAfk=true, strictPark=true, traceTest=true, engineOff=true, autoRescue=true, transitionNoclip=true, cameraFix=true, autoRetry=true, retryDelay=10, retryLimit=3, neutral=true, autoCollect=true, exitVehicle=true, single=false,
    autoMinimize=false, warehouse=true, warehouseRepeat=true, warehouseWait=15, warehouseHold=1, parkingRadius=4, fitGround=true, groundLimit=3, faceNPC=true, autoRoute=true, autoEnter=true, enterRadius=0, preferredVehicle="", itemName="Peças", retrySeconds=15, confirmLimit=180, reverseFront=false, holdSeconds=4, maxLift=1, settle=0.8, frontGap=2.5, timeout=8, scale=100}
local gui = Instance.new("ScreenGui")
gui.Name="DMenorGroupAutoRota"
gui.ResetOnSpawn=false
gui.IgnoreGuiInset=true
gui.ZIndexBehavior=Enum.ZIndexBehavior.Sibling
gui.DisplayOrder=30
gui.Parent=playerGui
local colors={bg=Color3.fromRGB(12,12,14),card=Color3.fromRGB(23,22,22),border=Color3.fromRGB(56,50,39),text=Color3.fromRGB(246,243,236),muted=Color3.fromRGB(164,158,148),accent=Color3.fromRGB(231,196,104)}
local appearance={contrastObjects={},tints={}}
function appearance.contrast(color)
    return color.R*0.2126+color.G*0.7152+color.B*0.0722>0.5 and Color3.fromRGB(9,15,22) or Color3.fromRGB(255,255,255)
end
local links, fields, switches, accentObjects = {}, {}, {}, {}
local logLines, completed, currentPoint = {}, 0, 0
local resize
local function make(class,parent,props)
    local obj=Instance.new(class)
    for k,v in pairs(props or {}) do obj[k]=v end
    obj.Parent=parent
    return obj
end
local function round(obj,r) make("UICorner",obj,{CornerRadius=UDim.new(0,r or 12)}) end
local function stroke(obj) return make("UIStroke",obj,{Color=colors.border,Thickness=1}) end
local function text(parent,value,pos,size,fontSize,color)
    local obj=make("TextLabel",parent,{Text=value,Position=pos,Size=size,
        BackgroundTransparency=1,Font=Enum.Font.Gotham,TextSize=fontSize or 13,
        TextColor3=color or colors.text,TextXAlignment=Enum.TextXAlignment.Left})
    if color==colors.accent then table.insert(accentObjects,{obj,"TextColor3"}) end
    return obj
end
local function paintAccent(obj,property)
    table.insert(accentObjects,{obj,property})
    obj[property]=colors.accent
end
local function action(parent,value,pos,size,accent)
    local obj=make("TextButton",parent,{Text=value,Position=pos,Size=size,
        BackgroundColor3=accent and colors.accent or colors.card,
        TextColor3=accent and appearance.contrast(colors.accent) or colors.text,
        Font=Enum.Font.GothamBold,TextSize=13,AutoButtonColor=false})
    round(obj,10)
    if accent then paintAccent(obj,"BackgroundColor3");table.insert(appearance.contrastObjects,obj) else stroke(obj) end
    obj.MouseEnter:Connect(function()
        TweenService:Create(obj,TweenInfo.new(0.12),{BackgroundTransparency=0.2}):Play()
    end)
    obj.MouseLeave:Connect(function()
        TweenService:Create(obj,TweenInfo.new(0.12),{BackgroundTransparency=0}):Play()
    end)
    return obj
end
local panel=make("Frame",gui,{Size=UDim2.fromOffset(660,700),AnchorPoint=Vector2.new(0.5,0.5),
    Position=UDim2.fromScale(0.5,0.5),BackgroundColor3=colors.bg,ClipsDescendants=true})
round(panel,22)
appearance.panelBorder=stroke(panel)
appearance.panelBorder.Color=colors.accent:Lerp(colors.border,0.82)
table.insert(appearance.tints,{appearance.panelBorder,"Color",0.82,colors.border})
make("UIGradient",panel,{Rotation=90,Color=ColorSequence.new(Color3.fromRGB(17,24,36),colors.bg)})
local panelScale=make("UIScale",panel,{Scale=1})
local header=make("Frame",panel,{BackgroundTransparency=1,Size=UDim2.new(1,-114,0,88),Active=true})
appearance.logoPlate=make("Frame",header,{Position=UDim2.fromOffset(22,22),Size=UDim2.fromOffset(44,44),BackgroundColor3=colors.accent:Lerp(colors.bg,0.88)})
round(appearance.logoPlate,13)
table.insert(appearance.tints,{appearance.logoPlate,"BackgroundColor3",0.88,colors.bg})
local logo=text(appearance.logoPlate,"DM",UDim2.fromOffset(0,0),UDim2.fromScale(1,1),19,colors.accent)
logo.Font=Enum.Font.GothamBold;logo.TextXAlignment=Enum.TextXAlignment.Center
text(header,"D’MENOR GROUP",UDim2.fromOffset(80,15),UDim2.fromOffset(295,27),24).Font=Enum.Font.GothamBold
text(header,"D’Menor Group · Ilha Bela",UDim2.fromOffset(81,43),UDim2.fromOffset(300,18),12,colors.muted)
text(header,"AUTO ROTA · D’MENOR GROUP",UDim2.fromOffset(81,64),UDim2.fromOffset(350,14),9,colors.accent)
text(header,"V1.3",UDim2.new(1,-82,0,23),UDim2.fromOffset(64,20),11,colors.muted).TextXAlignment=Enum.TextXAlignment.Right
local minimize=action(panel,"—",UDim2.new(1,-100,0,25),UDim2.fromOffset(34,34))
local close=action(panel,"×",UDim2.new(1,-56,0,25),UDim2.fromOffset(34,34))
local tabs=make("Frame",panel,{Position=UDim2.fromOffset(20,94),Size=UDim2.new(1,-40,0,44),BackgroundTransparency=1})
local pages, tabButtons = {}, {}
local tabNames={"Rota","Fábrica","Ajustes","Registro"}
appearance.tabIndicators={}
for i,name in ipairs(tabNames) do
    local btn=action(tabs,name,UDim2.new((i-1)/#tabNames,3,0,0),UDim2.new(1/#tabNames,-6,1,0))
    tabButtons[name]=btn
    local indicator=make("Frame",btn,{Position=UDim2.new(0.28,0,1,-3),Size=UDim2.new(0.44,0,0,2),BorderSizePixel=0,BackgroundColor3=colors.accent,Visible=i==1})
    round(indicator,1);paintAccent(indicator,"BackgroundColor3");appearance.tabIndicators[name]=indicator
    local page=make("ScrollingFrame",panel,{Position=UDim2.fromOffset(20,152),
        Size=UDim2.new(1,-40,1,-250),BackgroundTransparency=1,BorderSizePixel=0,
        ScrollBarThickness=3,ScrollBarImageColor3=colors.accent,
        AutomaticCanvasSize=Enum.AutomaticSize.Y,CanvasSize=UDim2.new(),Visible=i==1})
    make("UIPadding",page,{PaddingTop=UDim.new(0,2),PaddingBottom=UDim.new(0,8),PaddingLeft=UDim.new(0,2),PaddingRight=UDim.new(0,6)})
    make("UIListLayout",page,{Padding=UDim.new(0,10),SortOrder=Enum.SortOrder.LayoutOrder})
    pages[name]=page
end
local startButton
local function selectTab(name)
    if startButton and not busy then startButton.Text=name=="Fábrica" and "Iniciar armação" or "Iniciar rota" end
    for key,page in pairs(pages) do
        page.Visible=key==name
        local selected=key==name
        appearance.tabIndicators[key].Visible=selected
        tabButtons[key].TextColor3=selected and colors.accent or colors.muted
        tabButtons[key].BackgroundColor3=selected and colors.accent:Lerp(colors.bg,0.88) or colors.card
        local outline=tabButtons[key]:FindFirstChildOfClass("UIStroke")
        if outline then outline.Color=selected and colors.accent:Lerp(colors.border,0.35) or colors.border end
    end
end
for name,btn in pairs(tabButtons) do btn.Activated:Connect(function() selectTab(name) end) end
local function card(page,height)
    local obj=make("Frame",page,{Size=UDim2.new(1,0,0,height),BackgroundColor3=colors.card})
    round(obj,12);stroke(obj)
    return obj
end
local overview=card(pages.Rota,112)
overview.LayoutOrder=-100
text(overview,"SESSÃO",UDim2.fromOffset(14,12),UDim2.fromOffset(100,16),10,colors.muted)
local stateBadge=text(overview,"PRONTO",UDim2.new(1,-225,0,12),UDim2.fromOffset(210,16),9,colors.accent)
stateBadge.TextXAlignment=Enum.TextXAlignment.Right
local pointLabel=text(overview,"Ponto — / "..#DATA.points,UDim2.fromOffset(14,35),UDim2.new(1,-28,0,26),21)
pointLabel.Font=Enum.Font.GothamBold
local progressBack=make("Frame",overview,{Position=UDim2.fromOffset(14,76),Size=UDim2.new(1,-28,0,5),BackgroundColor3=colors.border})
round(progressBack,3)
local progressFill=make("Frame",progressBack,{Size=UDim2.fromScale(0,1),BackgroundColor3=colors.accent})
round(progressFill,3);paintAccent(progressFill,"BackgroundColor3")
local countLabel=text(overview,"0 interações nesta sessão",UDim2.fromOffset(14,88),UDim2.new(1,-28,0,15),10,colors.muted)
do
    local live=card(pages.Rota,164);live.LayoutOrder=-95
    appearance.live={metrics={}}
    text(live,"VEÍCULO E ESTACIONAMENTO",UDim2.fromOffset(14,10),UDim2.fromOffset(255,15),10,colors.muted)
    appearance.live.badge=text(live,"AGUARDANDO",UDim2.new(1,-199,0,10),UDim2.fromOffset(184,15),9,colors.muted)
    appearance.live.badge.TextXAlignment=Enum.TextXAlignment.Right
    appearance.live.name=text(live,"Nenhum veículo selecionado",UDim2.fromOffset(14,29),UDim2.new(1,-28,0,23),16)
    appearance.live.name.Font=Enum.Font.GothamBold
    local tiles=make("Frame",live,{Position=UDim2.fromOffset(14,60),Size=UDim2.new(1,-28,0,52),BackgroundTransparency=1})
    for i,label in ipairs({"MARCHA","FREIO DE MÃO","MOTOR","MOVIMENTO"}) do
        local tile=make("Frame",tiles,{Position=UDim2.new((i-1)/4,3,0,0),Size=UDim2.new(1/4,-6,1,0),BackgroundColor3=colors.bg})
        round(tile,9)
        text(tile,label,UDim2.fromOffset(9,7),UDim2.new(1,-18,0,12),8,colors.muted)
        local value=text(tile,"—",UDim2.fromOffset(9,24),UDim2.new(1,-18,0,21),13,colors.text)
        value.Font=Enum.Font.GothamBold;appearance.live.metrics[i]=value
    end
    appearance.live.fuel=text(live,"Gasolina —",UDim2.fromOffset(14,121),UDim2.new(0.5,-20,0,16),11,colors.muted)
    appearance.live.health=text(live,"Vida —",UDim2.new(0.5,6,0,121),UDim2.new(0.5,-20,0,16),11,colors.muted)
    local fuelBack=make("Frame",live,{Position=UDim2.fromOffset(14,144),Size=UDim2.new(0.5,-20,0,4),BackgroundColor3=colors.border})
    local healthBack=make("Frame",live,{Position=UDim2.new(0.5,6,0,144),Size=UDim2.new(0.5,-20,0,4),BackgroundColor3=colors.border})
    round(fuelBack,2);round(healthBack,2)
    appearance.live.fuelFill=make("Frame",fuelBack,{Size=UDim2.fromScale(0,1),BackgroundColor3=colors.accent});round(appearance.live.fuelFill,2);paintAccent(appearance.live.fuelFill,"BackgroundColor3")
    appearance.live.healthFill=make("Frame",healthBack,{Size=UDim2.fromScale(0,1),BackgroundColor3=colors.accent});round(appearance.live.healthFill,2);paintAccent(appearance.live.healthFill,"BackgroundColor3")
end
local statusCard=card(pages.Rota,112)
statusCard.LayoutOrder=-90
text(statusCard,"ATIVIDADE",UDim2.fromOffset(14,10),UDim2.fromOffset(200,14),10,colors.muted)
local status=text(statusCard,"Sente no banco do motorista para começar.",UDim2.fromOffset(14,30),UDim2.new(1,-28,0,72),12)
status.TextWrapped=true;status.TextYAlignment=Enum.TextYAlignment.Top
function appearance.section(page,label)
    local heading=text(page,label,UDim2.new(),UDim2.new(1,-10,0,23),10,colors.muted)
    heading.Font=Enum.Font.GothamBold
end
local function fieldRow(page,title,description,default)
    local row=card(page,64);row:SetAttribute("DMField",title)
    local heading=text(row,title,UDim2.fromOffset(14,9),UDim2.new(1,-100,0,18),12)
    heading.Font=Enum.Font.GothamMedium;heading.TextTruncate=Enum.TextTruncate.AtEnd
    local detail=text(row,description,UDim2.fromOffset(14,33),UDim2.new(1,-28,0,24),10,colors.muted)
    detail.TextWrapped=true;detail.TextYAlignment=Enum.TextYAlignment.Top
    local box=make("TextBox",row,{Position=UDim2.new(1,-82,0,8),Size=UDim2.fromOffset(68,25),Text=tostring(default),ClearTextOnFocus=false,BackgroundColor3=colors.bg,TextColor3=colors.text,TextSize=12,Font=Enum.Font.GothamMedium})
    round(box,7);local outline=stroke(box)
    box.Focused:Connect(function() outline.Color=colors.accent end)
    box.FocusLost:Connect(function() outline.Color=colors.border end)
    if type(default)=="string" then
        row.Size=UDim2.new(1,0,0,88);box.Position=UDim2.fromOffset(14,53);box.Size=UDim2.new(1,-28,0,25);detail.Size=UDim2.new(1,-28,0,16)
    end
    table.insert(fields,box);return box
end

local startAt=fieldRow(pages.Rota,"Ponto inicial","Retoma a partir desta parada · 1–"..#DATA.points,1)
local endAt=fieldRow(pages.Rota,"Limite de ponto","0 = seguir os Destinos do jogo",0)
local interval=fieldRow(pages.Rota,"Intervalo entre pontos","Tempo após retornar ao banco · 2–120 s",4)
local function switchRow(page,title,description,read,write)
    local row=card(page,56);row:SetAttribute("DMOption",title)
    local heading=text(row,title,UDim2.fromOffset(14,7),UDim2.new(1,-72,0,18),12)
    heading.TextTruncate=Enum.TextTruncate.AtEnd
    local detail=text(row,description,UDim2.fromOffset(14,29),UDim2.new(1,-28,0,20),9,colors.muted);detail.TextWrapped=true
    local btn=make("TextButton",row,{Text="",Position=UDim2.new(1,-52,0,9),Size=UDim2.fromOffset(38,22),BackgroundColor3=colors.bg,BorderSizePixel=0,AutoButtonColor=false});round(btn,11)
    local knob=make("Frame",btn,{Size=UDim2.fromOffset(16,16),Position=UDim2.fromOffset(3,3),BackgroundColor3=colors.muted,BorderSizePixel=0});round(knob,8)
    local function render()
        local enabled=read();btn.BackgroundColor3=enabled and colors.accent:Lerp(colors.bg,0.68) or colors.bg
        knob.Position=UDim2.fromOffset(enabled and 19 or 3,3);knob.BackgroundColor3=enabled and colors.accent or colors.muted
    end
    btn.Activated:Connect(function() if not busy then write(not read());render() end end)
    table.insert(switches,render);render();return btn
end

switchRow(pages.Rota,"Identificar rota automaticamente","Usa o marcador Destino, inclusive ao retomar",function() return cfg.autoRoute end,function(v) cfg.autoRoute=v end)
switchRow(pages.Rota,"Usar meu galpão","Sem rota ativa, vai ao galpão e inicia com E",function() return cfg.warehouse end,function(v) cfg.warehouse=v end)
switchRow(pages.Rota,"Reiniciar pelo galpão","Ao terminar, retorna e começa outra rota",function() return cfg.warehouseRepeat end,function(v) cfg.warehouseRepeat=v end)
switchRow(pages.Rota,"Repetir percurso","Volta ao ponto inicial selecionado",function() return repeatRoute end,function(v) repeatRoute=v end)
switchRow(pages.Rota,"Testar só um ponto","Executa apenas o ponto inicial",function() return cfg.single end,function(v) cfg.single=v end)
appearance.section(pages.Ajustes,"VEÍCULO E ACESSO")
switchRow(pages.Ajustes,"Entrar no carro ao iniciar","Seleciona somente veículos com seu proprietário",function() return cfg.autoEnter end,function(v) cfg.autoEnter=v end)
local enterRadiusField=fieldRow(pages.Ajustes,"Alcance para entrar no carro","0 = qualquer distância no mapa carregado",0)
local preferredField=fieldRow(pages.Ajustes,"Modelo de veículo preferido","Opcional: modelo entre seus veículos","")
preferredField.PlaceholderText="Entre os seus"
appearance.section(pages.Ajustes,"COLETA E ESTACIONAMENTO")
switchRow(pages.Ajustes,"Coleta automática","Desligado: percorre apenas a rota",function() return cfg.autoCollect end,function(v) cfg.autoCollect=v end)
switchRow(pages.Ajustes,"Estacionar de frente ao NPC","Ajusta a orientação antes de verificar colisões",function() return cfg.faceNPC end,function(v) cfg.faceNPC=v end)
switchRow(pages.Ajustes,"Sair do veículo","Sai somente pela frente antes de coletar",function() return cfg.exitVehicle end,function(v) cfg.exitVehicle=v end)
appearance.section(pages.Ajustes,"PROTEÇÃO DO VEÍCULO")
switchRow(pages.Ajustes,"Monitorar perdas por teleporte","Interrompe na primeira perda; exige campo de condição legível",function() return cfg.traceTest end,function(v) cfg.traceTest=v end)
switchRow(pages.Ajustes,"Travar N e freio de mão","Vigia os estados e segura o movimento durante o ajuste",function() return cfg.neutral end,function(v) cfg.neutral=v;cfg.strictPark=v end)
switchRow(pages.Ajustes,"Desligar motor durante a rota","Confere IsOn na interface ativa; não altera a gasolina",function() return cfg.engineOff end,function(v) cfg.engineOff=v end)
switchRow(pages.Ajustes,"Desatolar automaticamente","Endireita seu carro e busca espaço livre em até 36 studs",function() return cfg.autoRescue end,function(v) cfg.autoRescue=v end)
switchRow(pages.Ajustes,"Noclip nas transições","Personagem e carro: restaura colisões logo após reposicionar",function() return cfg.transitionNoclip end,function(v) cfg.transitionNoclip=v end)
switchRow(pages.Ajustes,"Corrigir câmera na coleta","Enquadra o NPC e aguarda a opção aparecer antes do E",function() return cfg.cameraFix end,function(v) cfg.cameraFix=v end)
switchRow(pages.Ajustes,"Anti-AFK","Envia atividade após um período de inatividade",function() return cfg.antiAfk end,function(v) cfg.antiAfk=v end)
switchRow(pages.Ajustes,"Minimizar ao iniciar","Acompanha a execução pela bolinha",function() return cfg.autoMinimize end,function(v) cfg.autoMinimize=v end)
appearance.section(pages.Ajustes,"RECUPERAÇÃO E TEMPOS")
switchRow(pages.Ajustes,"Corrigir e retomar após erro","Relê o Destino e procura novamente seu motorista",function() return cfg.autoRetry end,function(v) cfg.autoRetry=v;if not v then cancelAutoRetry(true) end end)
local recoveryDelayField=fieldRow(pages.Ajustes,"Espera após erro","Teclas soltas durante a espera · 3–120 s",10)
local recoveryLimitField=fieldRow(pages.Ajustes,"Limite de recuperação","Erros consecutivos sem nova coleta · 1–10",3)
local warehouseWaitField=fieldRow(pages.Ajustes,"Espera pelo novo Destino","Antes de considerar que não há rota · 8–60 s",15)
local warehouseHoldField=fieldRow(pages.Ajustes,"Tempo do E no galpão","Separado do E das coletas · 0,3–8 s",1)
local settleField=fieldRow(pages.Ajustes,"Estabilização do carro","Espera após chegar ao destino · 0,5–5 s",0.8)
local frontField=fieldRow(pages.Ajustes,"Distância da ponta","Espaço à frente da carroceria · 1–5 studs",2.5)
local timeoutField=fieldRow(pages.Ajustes,"Espera pela coleta","Tempo para encontrar o prompt · 2–20 s",8)
local itemField=fieldRow(pages.Ajustes,"Item da mochila","Nome no cartão; confere o contador via B","Peças")
itemField.PlaceholderText="Peças"
local retryField=fieldRow(pages.Ajustes,"Espera entre tentativas","Permanece na mesma coleta · 5–120 s",15)
local confirmField=fieldRow(pages.Ajustes,"Prazo para confirmar","Ao esgotar, para sem avançar · 30–600 s",180)
local holdField=fieldRow(pages.Ajustes,"Tempo segurando a coleta","Mínimo informado para esta rota · 4–10 s",4)
switchRow(pages.Ajustes,"Inverter frente do veículo","Use se a frente for identificada ao contrário",function() return cfg.reverseFront end,function(v) cfg.reverseFront=v end)
switchRow(pages.Ajustes,"Adaptar à inclinação da rua","Lê o piso sob as rodas antes de mover",function() return cfg.fitGround end,function(v) cfg.fitGround=v end)
appearance.section(pages.Ajustes,"GEOMETRIA E AJUSTE FINO")
local parkingField=fieldRow(pages.Ajustes,"Ajuste fino de estacionamento","Deslocamento perto da vaga · 0–6 studs",4)
local groundField=fieldRow(pages.Ajustes,"Correção máxima pelo piso","Diferença da altura gravada · 0–6 studs",3)
local heightField=fieldRow(pages.Ajustes,"Ajuste de altura do destino","Folga adicional apenas para rodas · 0–1 stud",1)
local scaleField=fieldRow(pages.Ajustes,"Tamanho da interface","Escala do painel · 75–115%",100)
local resetRow=card(pages.Ajustes,56)
local resetButton=action(resetRow,"Restaurar ajustes padrão",UDim2.fromOffset(10,10),UDim2.new(1,-20,0,35))
resetButton.Activated:Connect(function()
    if busy then return end
    cancelAutoRetry(true)
    cfg.antiAfk=true
    cfg.autoRescue=true;cfg.transitionNoclip=true;cfg.cameraFix=true;cfg.autoRetry=true;cfg.retryDelay=10;cfg.retryLimit=3
    recoveryDelayField.Text="10";recoveryLimitField.Text="3"
    cfg.strictPark=true;cfg.traceTest=true;cfg.engineOff=true;cfg.neutral=true;cfg.autoCollect=true;cfg.exitVehicle=true;cfg.single=false;cfg.autoMinimize=false;cfg.warehouse=true;cfg.warehouseRepeat=true;cfg.warehouseWait=15;cfg.warehouseHold=1;cfg.parkingRadius=4;cfg.fitGround=true;cfg.groundLimit=3;cfg.faceNPC=true;cfg.autoRoute=true;cfg.autoEnter=true;cfg.enterRadius=0;cfg.preferredVehicle=""
    cfg.settle=0.8;cfg.frontGap=2.5;cfg.timeout=8;cfg.scale=100;cfg.maxLift=1;cfg.reverseFront=false;cfg.holdSeconds=4;cfg.itemName="Peças";cfg.retrySeconds=15;cfg.confirmLimit=180;repeatRoute=false
    startAt.Text="1";endAt.Text="0";interval.Text="4";settleField.Text="0.8";warehouseWaitField.Text="15";warehouseHoldField.Text="1";enterRadiusField.Text="0";preferredField.Text=""
    frontField.Text="2.5";timeoutField.Text="8";scaleField.Text="100";heightField.Text="1";groundField.Text="3";parkingField.Text="4";holdField.Text="4";itemField.Text="Peças";retryField.Text="15";confirmField.Text="180"
    if fabrication.quantityField then
        fabrication.quantityField.Text="1"
        fabrication.intervalField.Text="3";fabrication.timeoutField.Text="30";fabrication.holdField.Text="0"
    end
    for _,render in ipairs(switches) do render() end
    if resize then resize() end
end)
local logCard=card(pages.Registro,255)
local logScroll=make("ScrollingFrame",logCard,{Position=UDim2.fromOffset(10,10),Size=UDim2.new(1,-20,1,-20),
    BackgroundTransparency=1,BorderSizePixel=0,ScrollBarThickness=3,
    AutomaticCanvasSize=Enum.AutomaticSize.Y,CanvasSize=UDim2.new()})
local logBox=make("TextBox",logScroll,{Position=UDim2.fromOffset(2,2),Size=UDim2.new(1,-12,0,225),AutomaticSize=Enum.AutomaticSize.Y,
    BackgroundTransparency=1,Text="O histórico aparece aqui.",TextEditable=false,ClearTextOnFocus=false,
    MultiLine=true,TextWrapped=true,Font=Enum.Font.Code,TextSize=11,TextColor3=colors.muted,
    TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Top})
local logControls=card(pages.Registro,55)
local copyLog=action(logControls,"Selecionar registro",UDim2.fromOffset(10,10),UDim2.new(0.6,-15,0,35))
copyLog.Activated:Connect(function() logBox:CaptureFocus();logBox.CursorPosition=#logBox.Text+1;logBox.SelectionStart=1 end)
local clearLog=action(logControls,"Limpar",UDim2.new(0.6,0,0,10),UDim2.new(0.4,-10,0,35))
clearLog.Activated:Connect(function() logLines={};logBox.Text="Registro limpo." end)
local footer=make("Frame",panel,{Position=UDim2.new(0,20,1,-82),Size=UDim2.new(1,-40,0,66),BackgroundTransparency=1})
startButton=action(footer,"Iniciar rota",UDim2.fromOffset(0,0),UDim2.new(0.66,-6,0,38),true)
local stopButton=action(footer,"Parar",UDim2.new(0.66,6,0,0),UDim2.new(0.34,-6,0,38))
stopButton.BackgroundColor3=Color3.fromRGB(46,24,33);stopButton.TextColor3=Color3.fromRGB(255,148,164)
appearance.footerStatus=text(footer,"D’Menor Group · Ctrl direito minimiza",UDim2.fromOffset(0,45),UDim2.new(1,0,0,14),9,colors.muted)
local bubble=make("TextButton",gui,{Name="BolinhaFlutuante",AnchorPoint=Vector2.new(0.5,0.5),
    Position=UDim2.new(0,50,0.5,0),Size=UDim2.fromOffset(64,64),BackgroundColor3=colors.bg,
    Text="DM",TextSize=20,Font=Enum.Font.GothamBold,TextColor3=colors.accent,
    AutoButtonColor=false,Visible=false})
round(bubble,32)
do
    local brand=text(bubble,"D’MENOR GROUP",UDim2.fromOffset(0,45),UDim2.new(1,0,0,11),8,colors.muted)
    brand.TextXAlignment=Enum.TextXAlignment.Center
end
local ring=stroke(bubble);ring.Color=colors.accent;ring.Thickness=2;paintAccent(ring,"Color");paintAccent(bubble,"TextColor3")
local dot=make("Frame",bubble,{Position=UDim2.new(1,-13,0,2),Size=UDim2.fromOffset(11,11),BackgroundColor3=colors.muted})
round(dot,6);stroke(dot)
local function setMinimized(value) panel.Visible=not value;bubble.Visible=value end
minimize.Activated:Connect(function() setMinimized(true) end)
close.Activated:Connect(function() running=false;gui:Destroy() end)
local function viewport()
    return workspace.CurrentCamera and workspace.CurrentCamera.ViewportSize or Vector2.new(1280,720)
end
resize=function()
    local view=viewport()
    local normalized=scaleField.Text:gsub(",",".")
    local wanted=tonumber(normalized) or 100
    wanted=math.clamp(wanted,75,115)/100
    panelScale.Scale=math.min(wanted,(view.X-24)/660,(view.Y-32)/700)
end
scaleField.FocusLost:Connect(resize)
local function draggable(handle,target)
    local inputStart,positionStart,dragInput,dragging,moved,endedAt
    handle.InputBegan:Connect(function(input)
        if input.UserInputType~=Enum.UserInputType.MouseButton1 and input.UserInputType~=Enum.UserInputType.Touch then return end
        dragging=true;moved=false;inputStart=input.Position;positionStart=target.AbsolutePosition+target.AbsoluteSize/2
        dragInput=input
    end)
    table.insert(links,UserInputService.InputChanged:Connect(function(input)
        if not dragging then return end
        if input.UserInputType~=Enum.UserInputType.MouseMovement and input~=dragInput then return end
        local delta=input.Position-inputStart
        if delta.Magnitude>6 then moved=true end
        if not moved then return end
        local view=viewport();local half=target.AbsoluteSize/2
        local pos=positionStart+Vector2.new(delta.X,delta.Y)
        target.Position=UDim2.fromOffset(math.clamp(pos.X,half.X+4,math.max(half.X+4,view.X-half.X-4)),
            math.clamp(pos.Y,half.Y+4,math.max(half.Y+4,view.Y-half.Y-4)))
    end))
    table.insert(links,UserInputService.InputEnded:Connect(function(input)
        if input==dragInput or input.UserInputType==Enum.UserInputType.MouseButton1 then
            dragging=false;endedAt=os.clock()
        end
    end))
    return function() return moved and (dragging or (endedAt and os.clock()-endedAt<0.3)) end
end
draggable(header,panel)
local bubbleDragged=draggable(bubble,bubble)
bubble.Activated:Connect(function() if not bubbleDragged() then setMinimized(false) end end)
table.insert(links,UserInputService.InputBegan:Connect(function(input,processed)
    if not processed and not UserInputService:GetFocusedTextBox() and input.KeyCode==Enum.KeyCode.RightControl then
        setMinimized(panel.Visible)
    end
end))
local camera=workspace.CurrentCamera
if camera then table.insert(links,camera:GetPropertyChangedSignal("ViewportSize"):Connect(resize)) end
gui.Destroying:Connect(function() cancelAutoRetry(true);running=false;for _,link in ipairs(links) do link:Disconnect() end end)
local function updateState(value)
    stateBadge.Text=value
    stateBadge.TextColor3=running and colors.accent or colors.muted
    dot.BackgroundColor3=running and colors.accent or colors.muted
    startButton.Text=busy and (fabrication.active and "Armação em andamento..." or "Em execução...") or (pages["Fábrica"].Visible and "Iniciar armação" or "Iniciar rota")
    for _,box in ipairs(fields) do box.TextEditable=not busy end
    if appearance.footerStatus then appearance.footerStatus.Text=busy and "Operação em andamento · Parar encerra e libera as teclas" or "D’Menor Group · Ctrl direito minimiza" end
end
appearance.refreshState=function()
    stateBadge.TextColor3=running and colors.accent or colors.muted
    dot.BackgroundColor3=running and colors.accent or colors.muted
end
function appearance.renderTelemetry(model,seat,state,force)
    local ui=appearance.live
    if not ui then return end
    appearance.lastTelemetry={model=model,seat=seat,state=state}
    if not force and os.clock()-(appearance.telemetryAt or 0)<0.2 then return end
    appearance.telemetryAt=os.clock()
    local amber=Color3.fromRGB(255,193,107)
    local red=Color3.fromRGB(255,132,155)
    local valid=model and model.Parent and seat and seat.Parent
    ui.name.Text=valid and model.Name or "Nenhum veículo selecionado"
    for _,label in ipairs(ui.metrics) do label.Text="—";label.TextColor3=colors.muted end
    ui.fuel.Text="Gasolina —";ui.health.Text="Vida —"
    ui.fuelFill.Size=UDim2.fromScale(0,1);ui.healthFill.Size=UDim2.fromScale(0,1)
    ui.badge.Text="AGUARDANDO VEÍCULO";ui.badge.TextColor3=colors.muted
    if not valid then return end
    local hum=player.Character and player.Character:FindFirstChildOfClass("Humanoid")
    local seated=hum and hum.SeatPart==seat
    if state and state.interface.Parent and seated then
        local neutral=state.gear.Value==0
        local brake=state.brake.Value
        ui.metrics[1].Text=neutral and "N" or state.gear.Value==-1 and "R" or tostring(state.gear.Value)
        ui.metrics[1].TextColor3=neutral and colors.accent or amber
        ui.metrics[2].Text=brake and "P ATIVO" or "SOLTO";ui.metrics[2].TextColor3=brake and colors.accent or red
        ui.metrics[3].Text=state.engine.Value and "LIGADO" or "OFF";ui.metrics[3].TextColor3=state.engine.Value and amber or colors.accent
        local v=seat.AssemblyLinearVelocity
        local moving=Vector3.new(v.X,0,v.Z).Magnitude>0.15
        ui.metrics[4].Text=moving and (running and "CONTENDO" or "MOVENDO") or "PARADO"
        ui.metrics[4].TextColor3=moving and amber or colors.accent
        ui.badge.Text=neutral and brake and (running and "N/P CONFIRMADOS" or "N/P · INATIVO") or "AJUSTANDO N/P"
        ui.badge.TextColor3=neutral and brake and colors.accent or amber
        if running then dot.BackgroundColor3=neutral and brake and colors.accent or amber end
    else
        ui.metrics[4].Text=seated and "TRAVANDO" or "A PÉ"
        ui.badge.Text=seated and "CARREGANDO INTERFACE" or "LEITURA DO VEÍCULO"
        ui.badge.TextColor3=seated and amber or colors.muted
    end
    local info=model:FindFirstChild("Info")
    local data=info and info:FindFirstChild("Status")
    local function number(parent,name)
        local value=parent and parent:FindFirstChild(name)
        if value and (value:IsA("NumberValue") or value:IsA("IntValue")) then return value.Value end
    end
    local fuel=number(data,"Gasolina")
    local health=number(data,"Vida")
    local maximum=number(model,"VidaMax")
    if fuel then
        ui.fuel.Text=string.format("Gasolina %.2f%%",fuel)
        ui.fuelFill.Size=UDim2.fromScale(math.clamp(fuel/100,0,1),1)
        ui.fuelFill.BackgroundColor3=fuel<20 and red or colors.accent
    end
    if health then
        ui.health.Text=maximum and maximum>0 and string.format("Vida %.0f / %.0f",health,maximum) or string.format("Vida %.0f",health)
        local ratio=maximum and maximum>0 and math.clamp(health/maximum,0,1) or 0
        ui.healthFill.Size=UDim2.fromScale(ratio,1);ui.healthFill.BackgroundColor3=ratio<0.25 and red or colors.accent
    end
end
local function say(message)
    if not gui.Parent then return end
    status.Text=message
    table.insert(logLines,os.date("%H:%M:%S") .. "  " .. message)
    if #logLines>60 then table.remove(logLines,1) end
    logBox.Text=table.concat(logLines,"\n")
    print("[D’Menor Group] " .. message)
end
do
    local lastInput = os.clock()
    local lastPulse = -math.huge
    local warned = false
    local virtualUser

    local function keepAwake()
        local now = os.clock()
        if not cfg.antiAfk or not gui.Parent or now - lastPulse < 60 then return end
        lastPulse = now

        local camera = workspace.CurrentCamera
        local frame = camera and camera.CFrame or CFrame.new()
        local started, failure = pcall(function()
            virtualUser = virtualUser or game:GetService("VirtualUser")
            virtualUser:CaptureController()
            virtualUser:Button2Down(Vector2.zero, frame)
        end)
        local released, releaseFailure = true, nil
        if virtualUser then
            released, releaseFailure = pcall(function()
                virtualUser:Button2Up(Vector2.zero, frame)
            end)
        end
        if not started or not released then
            if not warned then
                warned = true
                say("Anti-AFK indisponível: " .. tostring(failure or releaseFailure))
            end
        else
            warned = false
        end
    end

    table.insert(links, player.Idled:Connect(keepAwake))
    table.insert(links, UserInputService.InputBegan:Connect(function()
        lastInput = os.clock()
    end))
    table.insert(links, game:GetService("RunService").Heartbeat:Connect(function()
        local now = os.clock()
        if now - lastInput >= 60 and now - lastPulse >= 60 then
            keepAwake()
        end
    end))
end
resize();selectTab("Rota")
local windowFocused=true
local shownCollectionPrompts=setmetatable({},{__mode="k"})
local promptService=game:GetService("ProximityPromptService")
table.insert(links,promptService.PromptShown:Connect(function(prompt) shownCollectionPrompts[prompt]=true end))
table.insert(links,promptService.PromptHidden:Connect(function(prompt) shownCollectionPrompts[prompt]=nil end))
local collectionCameraSession
local function restoreCollectionCamera()
    local session=collectionCameraSession
    collectionCameraSession=nil
    if not session then return end
    if session.link then session.link:Disconnect() end
    local cam=session.camera
    if not cam or not cam.Parent then return end
    local hum=player.Character and player.Character:FindFirstChildOfClass("Humanoid")
    pcall(function()
        cam.CameraSubject=hum or session.subject
        cam.CameraType=Enum.CameraType.Custom
    end)
end
gui.Destroying:Connect(restoreCollectionCamera)
local heldKeys={}
local function releaseKey(key)
    local token=heldKeys[key]
    local ok,err=pcall(function()
        game:GetService("VirtualInputManager"):SendKeyEvent(false,key,false,game)
    end)
    if ok and heldKeys[key]==token then heldKeys[key]=nil end
    return ok,err
end
local function releaseAllKeys()
    local pending={}
    for key in pairs(heldKeys) do table.insert(pending,key) end
    for _,key in ipairs(pending) do releaseKey(key) end
end
local function beginTimedKey(key,seconds)
    while not windowFocused do
        if not running or not gui.Parent then error("Ação cancelada antes de pressionar a tecla.",0) end
        task.wait(0.1)
    end
    if not running or not gui.Parent then error("Ação cancelada antes de pressionar a tecla.",0) end
    local token={}
    heldKeys[key]=token
    -- Temporizador separado do código que verifica a coleta.
    task.delay(seconds,function()
        if heldKeys[key]==token then releaseKey(key) end
    end)
    local ok,err=pcall(function()
        game:GetService("VirtualInputManager"):SendKeyEvent(true,key,false,game)
    end)
    if not ok then releaseKey(key);error(tostring(err),0) end
end
close.Activated:Connect(releaseAllKeys)
gui.Destroying:Connect(releaseAllKeys)
table.insert(links,UserInputService.WindowFocusReleased:Connect(function()
    windowFocused=false
    releaseAllKeys()
    if running then updateState("PAUSADO · VOLTE AO ROBLOX");say("Roblox perdeu o foco. Teclas soltas; aguardando você voltar ao jogo, sem cancelar a rota.") end
end))
table.insert(links,UserInputService.WindowFocused:Connect(function()
    windowFocused=true
    if running then updateState("EM EXECUÇÃO");say("Roblox em foco. Continuando a execução.") end
end))
local function active() return running and gui.Parent ~= nil end
local vehicleStateHook
local transitionInProgress=false
local function waitActive(seconds)
    local elapsed = 0
    while elapsed < seconds do
        if not active() then return false end
        if windowFocused then
            elapsed = elapsed + task.wait(math.min(0.05,seconds-elapsed))
            if vehicleStateHook and not transitionInProgress and active() and windowFocused then vehicleStateHook() end
        else
            task.wait(0.1)
        end
    end
    return active()
end
local function ownerField(name)
    local key=tostring(name):gsub("Á","a"):gsub("á","a"):lower():gsub("[%s_%-]","")
    local fields={owner=true,ownerid=true,owneruserid=true,ownername=true,
        dono=true,donoid=true,donouserid=true,dononome=true,
        proprietario=true,proprietarioid=true,proprietariouserid=true,
        vehicleowner=true,carowner=true,ownedby=true}
    return fields[key]==true
end
local function vehicleOwnership(model)
    local mine,other=false,false
    local evidence={}
    local function inspect(path,value)
        local isMine,isOther=false,false
        if typeof(value)=="Instance" then
            local owner=value:IsA("Player") and value or (value:IsA("Model") and Players:GetPlayerFromCharacter(value))
            if owner then isMine=owner.UserId==player.UserId;isOther=not isMine end
        elseif type(value)=="number" and value>0 then
            isMine=value==player.UserId;isOther=not isMine
        elseif type(value)=="string" and value~="" then
            isMine=value:lower()==player.Name:lower() or value==tostring(player.UserId)
            isOther=not isMine
        end
        if isMine or isOther then
            table.insert(evidence,path.."="..(typeof(value)=="Instance" and value.Name or tostring(value)))
            mine=mine or isMine;other=other or isOther
        end
    end
    local function inspectAttributes(obj)
        for name,value in pairs(obj:GetAttributes()) do
            if ownerField(name) then inspect(obj:GetFullName().." ["..name.."]",value) end
        end
    end
    inspectAttributes(model)
    local containers={config=true,configuration=true,values=true,data=true,settings=true,
        info=true,vehicleinfo=true,ownership=true,owner=true,dono=true}
    local function inspectChild(obj)
        inspectAttributes(obj)
        if ownerField(obj.Name) and (obj:IsA("ObjectValue") or obj:IsA("StringValue")
            or obj:IsA("IntValue") or obj:IsA("NumberValue")) then inspect(obj:GetFullName(),obj.Value) end
    end
    for _,child in ipairs(model:GetChildren()) do
        if not child:IsA("BasePart") and not child:IsA("LuaSourceContainer") then
            inspectChild(child)
            if containers[child.Name:lower()] and (child:IsA("Folder") or child:IsA("Configuration")) then
                for _,value in ipairs(child:GetChildren()) do inspectChild(value) end
            end
        end
    end
    local reason=table.concat(evidence,"; ")
    if mine and not other then return true,reason end
    if mine and other then return nil,"campos de dono conflitantes: "..reason end
    if other then return false,reason end
    local attributes,children={},{}
    for name in pairs(model:GetAttributes()) do table.insert(attributes,name) end
    table.sort(attributes)
    for _,child in ipairs(model:GetChildren()) do
        if #children>=10 then break end
        table.insert(children,child.Name.."<"..child.ClassName..">")
    end
    return nil,"nenhum proprietário reconhecido; atributos: "..(#attributes>0 and table.concat(attributes,", ") or "nenhum")..
        "; estrutura: "..table.concat(children,", ")
end
local function requireMyVehicle(model)
    local owned,reason=vehicleOwnership(model)
    if owned~=true then
        error("Não confirmei que "..model.Name.." é seu. "..tostring(reason)..". Não vou selecionar outro carro por proximidade.",0)
    end
end
-- Perfis observados: Toyota usa A-Chassis Interface; Pop 100 usa Interface.
local vehicleSupport={cache=setmetatable({},{__mode="k"})}
function vehicleSupport.model(seat)
    local cars=workspace:FindFirstChild("CarrosSpawnados")
    local model=seat
    while model and model.Parent~=cars do model=model.Parent end
    return cars and model or nil
end
function vehicleSupport.interface(seat)
    local model=vehicleSupport.model(seat)
    if not model then return nil end
    local expected=model.Name=="Pop 100" and "Interface" or model.Name=="Toyota" and "A-Chassis Interface" or nil
    local found={}
    local linked
    for _,name in ipairs({"A-Chassis Interface","Interface"}) do
        local interface=playerGui:FindFirstChild(name)
        local values=interface and interface:FindFirstChild("Values")
        local gear=values and values:FindFirstChild("Gear")
        local brake=values and values:FindFirstChild("PBrake")
        local engine=interface and interface:FindFirstChild("IsOn")
        local controls=interface and interface:FindFirstChild("Controls")
        if gear and (gear:IsA("NumberValue") or gear:IsA("IntValue")) and brake and brake:IsA("BoolValue")
            and engine and engine:IsA("BoolValue") and controls then
            local car=interface:FindFirstChild("Car")
            local matches=car and car:IsA("ObjectValue") and car.Value and (car.Value==model or car.Value==seat or seat:IsDescendantOf(car.Value))
            local other=car and car:IsA("ObjectValue") and car.Value and not matches
            if not other then
                if matches then
                    if linked and linked~=interface then return nil end
                    linked=interface
                end
                table.insert(found,interface)
            end
        end
    end
    if linked then return linked end
    for _,interface in ipairs(found) do if interface.Name==expected then return interface end end
    if #found==1 then return found[1] end
    return nil
end
-- As rodas físicas da Pop 100 são Part/Ball uniformes na captura da versão 19904.
function vehicleSupport.sphereRadius(part)
    if part:IsA("Part") and part.Shape==Enum.PartType.Ball then
        local size=part.Size
        if math.abs(size.X-size.Y)<=0.001 and math.abs(size.X-size.Z)<=0.001 then return size.X/2 end
    end
    return nil
end
function vehicleSupport.extent(part,pose,axis)
    local radius=vehicleSupport.sphereRadius(part)
    if radius then return radius*axis.Magnitude end
    local half=part.Size/2
    return math.abs(pose.RightVector:Dot(axis))*half.X+math.abs(pose.UpVector:Dot(axis))*half.Y+math.abs(pose.LookVector:Dot(axis))*half.Z
end
function vehicleSupport.profile(model,seat)
    local cached=vehicleSupport.cache[model]
    if cached then
        local valid=true
        for _,part in ipairs(cached.wheels) do if not part.Parent or not part:IsDescendantOf(model) then valid=false;break end end
        if valid then return cached end
    end
    local container=model:FindFirstChild("Wheels",true)
    local named={}
    for _,part in ipairs((container or model):GetDescendants()) do
        if part:IsA("BasePart") and ({FL=true,FR=true,RL=true,RR=true})[part.Name] then named[part.Name]=part end
    end
    local wheels,kind={},nil
    if named.FL and named.FR and named.RL and named.RR then
        wheels={named.FL,named.FR,named.RL,named.RR};kind="quatro rodas"
    elseif model.Name=="Pop 100" then
        -- Caminhos confirmados no relatório: não usa eixos, suspensão ou peças visuais.
        local frontSection=model:FindFirstChild("FrontSection")
        local rearSection=model:FindFirstChild("RearSection")
        local front=frontSection and frontSection:FindFirstChild("Wheel")
        local rear=rearSection and rearSection:FindFirstChild("Wheel")
        if front and rear and front:IsA("BasePart") and rear:IsA("BasePart") and front~=rear
            and front.CanCollide and rear.CanCollide and not front.Anchored and not rear.Anchored
            and vehicleSupport.sphereRadius(front) and vehicleSupport.sphereRadius(rear)
            and (front.Position-rear.Position).Magnitude>=0.75 then
            wheels={front,rear};kind="duas rodas";named.F=front;named.R=rear
 ... (790 KB restante(s))
