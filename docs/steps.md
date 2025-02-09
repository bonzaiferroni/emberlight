## add wasm run configuration
wasmJsBrowserRun -t --quiet

## add desktop run configuration
composeApp:run

## use material3
implementation(compose.material3)

## package app
composeApp:packageDeb
*project*/composeApp/build/compose/binaries/main
72.7 MB


