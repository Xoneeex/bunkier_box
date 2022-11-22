    local success = exports['bunkier_box']:StartBunkierBox()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end