```rs
fn main() {
    let socials: Vec<(&str,&str)> = vec![
        (
            "Github",
            "4lpaca-pin"
        ),
        (
            "Discord",
            "2lpa"
        ),
        (
            "Spotify",
            "https://open.spotify.com/user/31bykf54bb4omzpgoa4brsvzznwu"
        ),
        (
            "Steam",
            "4sas1337"
        ),
    ];

    let skill: Vec<&str> = vec![
        "LuaU",
        "Lua",
        "JavaScript",
        "Html",
        "CSS",
        "Rust",
        "Python",
        "Node.js",
        "Blender",
        "Electron",
        "Roblox Studio"
    ];

    let bio = format!(
        "Age {}, Backend , Application , Roblox User-Interface Developer",
        16
    );

    println!("{:?}\n{:?}\nNote: {}",socials,skill,bio);
}
```
