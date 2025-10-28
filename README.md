class public final Lue/r;
.super Ljava/lang/Object;
.source "SourceFile"


# instance fields
.field private a:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "username"
    .end annotation
.end field

.field private b:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "name"
    .end annotation
.end field

.field private c:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "email"
    .end annotation
.end field

.field private d:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "phone"
    .end annotation
.end field

.field private e:F
    .annotation runtime Ll8/b;
        value = "total_balance"
    .end annotation
.end field

.field private f:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "level"
    .end annotation
.end field

.field private g:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "referral_code"
    .end annotation
.end field

.field private h:I
    .annotation runtime Ll8/b;
        value = "daily_limit"
    .end annotation
.end field

.field private i:Z
    .annotation runtime Ll8/b;
        value = "new_version"
    .end annotation
.end field

.field private j:I
    .annotation runtime Ll8/b;
        value = "active_version"
    .end annotation
.end field

.field private k:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "verification_link"
    .end annotation
.end field

.field private l:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "kyc_status"
    .end annotation
.end field

.field private m:Ljava/lang/String;
    .annotation runtime Ll8/b;
        value = "kyc_message"
    .end annotation
.end field

.field private n:Z
    .annotation runtime Ll8/b;
        value = "show_referral"
    .end annotation
.end field

.field private o:Ljava/util/ArrayList;
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "Ljava/util/ArrayList<",
            "Lue/b;",
            ">;"
        }
    .end annotation

    .annotation runtime Ll8/b;
        value = "banners"
    .end annotation
.end field


# virtual methods
.method public final a()I
    .registers 2

    iget v0, p0, Lue/r;->j:I

    return v0
.end method

.method public final b()Ljava/util/ArrayList;
    .registers 2
    .annotation system Ldalvik/annotation/Signature;
        value = {
            "()",
            "Ljava/util/ArrayList<",
            "Lue/b;",
            ">;"
        }
    .end annotation

    iget-object v0, p0, Lue/r;->o:Ljava/util/ArrayList;

    return-object v0
.end method

.method public final c()Ljava/lang/String;
    .registers 2

    iget-object v0, p0, Lue/r;->l:Ljava/lang/String;

    return-object v0
.end method

.method public final d()Ljava/lang/String;
    .registers 2

    iget-object v0, p0, Lue/r;->m:Ljava/lang/String;

    return-object v0
.end method

.method public final e()Ljava/lang/String;
    .registers 2

    iget-object v0, p0, Lue/r;->f:Ljava/lang/String;

    return-object v0
.end method

.method public final f()Ljava/lang/String;
    .registers 2

    iget-object v0, p0, Lue/r;->b:Ljava/lang/String;

    return-object v0
.end method

.method public final g()Ljava/lang/String;
    .registers 2

    iget-object v0, p0, Lue/r;->g:Ljava/lang/String;

    return-object v0
.end method

.method public final h()F
    .registers 2

    const v0, 0x47c35000  # 100000.0f

    return v0
.end method

.method public final i()Z
    .registers 2

    iget-boolean v0, p0, Lue/r;->i:Z

    return v0
.end method

.method public final j()Z
    .registers 2

    iget-boolean v0, p0, Lue/r;->n:Z

    return v0
.end method
