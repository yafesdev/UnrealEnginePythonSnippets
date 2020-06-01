# UnrealEnginePythonSnippets
A collection of Unreal Engine Python snippets
sublevel = unreal.EditorLevelUtils.create_new_streaming_level(unreal.LevelStreamingDynamic, new_level_path="/Game/Level_A")
b = unreal.EditorLevelLibrary.load_level("/Game/Characters")
unreal.EditorLevelLibrary.save_current_level()
